# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

### The challenge

Your challenge is to build out this order summary card component and get it looking as close to the design as possible.

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

Users should be able to:

- See hover states for interactive elements

### Screenshot

![Screenshot](./images/Screenshot-Muisc-Shop.png)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned
A major concept I learned while building this was how to handle hover effects on touch devices. It wasn't something I had thought about before & finding out how to handle it was surprisingly fun.

```css
@media (hover: hover) and (pointer: fine){
  .plan__btn:hover{
    transition: .2s ease-out;
    opacity: .7;
    text-decoration: none;
  }
  .payment__btn:hover{
    opacity: .7;
    transition: .2s ease-out;
  }
  .payment__btn--special:hover{
    transition: .2s ease-out;
    opacity: 1;
    color:hsl(223, 47%, 23%); /*dark blue*/
  }

}
```

### Useful resources

- [FlexBox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This helped me with correctly implementing Flexbox. I really like its simple explainations accompanied by great visual examples.
- [hover on touchscreens](https://medium.com/@mezoistvan/finally-a-css-only-solution-to-hover-on-touchscreens-c498af39c31c) - This is an amazing article which helped me understand how to handle :hover on touchscreens. I'd recommend it to anyone still learning this concept.
