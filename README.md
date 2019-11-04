# what-i-learned-in-week-8

## Functional programming

Calling functions from within other functions also returning values of functions within other functions.

*Example:*
```
function call(func) {
  func();
}

function twoFuncs(func1, func2) {
  return func2(func1());
}
```
### Uptown-func

The object of this exercise was to practice placing functions inside other functions properly.
https://github.com/phenix1229/uptown-func

### Promptulate

The object of this exercise was to use the `prompt` method to take in user input and pass it to the calculator function and manipulate the DOM to show the result.
https://github.com/phenix1229/promptulate

### your-info-web-app

This exercise was to convert the previous Node app into a web app using the `prompt` method and DOM manipulation.
https://github.com/phenix1229/your-info-web-app

### Funculate

This exercise was to alter the calculator app to use functional programming.
https://github.com/phenix1229/funculate/blob/master/calculate.js

---

## Event listeners

Adding Event listeners in order to manipulate the DOM based on user actions.

### Domosaur

In this exercise, event listeners were added to perform actions on page elements when they were clicked.
https://github.com/phenix1229/domosaur

### Extinction-event

https://github.com/phenix1229/extinction-event


---

## Miscellaneous
### for of loops
A quicker form of for loops for simple functions where you are only doing one thing for each index.

*Example:*
```
const colors = [black, white, blue]

for (i = 0; i < colors.length; i++){
    const color = colors[i];
    console.log(color);
}

Becomes:

for (const color of colors){
    console.log(color);
}
```
