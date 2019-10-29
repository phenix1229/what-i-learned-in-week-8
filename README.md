# what-i-learned-in-week-8
## Functional programming


---

## Miscellaneous
### for of loops
A quicker form of for loops for simple functions where you are only doing one thing for each index.
*Example*
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
