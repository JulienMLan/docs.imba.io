# Styling
imba is strongly opinionated about many things. However, when it comes to styling your code, imba gives you many options. 

## Styles within Comment Blocks
This is the prefered way to style your tags in imba. Comment blocks can either be scoped:
```css
### css scoped
body {
    padding: 10px; 
}
###
```
or unscoped:
 ```css
### css
body {
    padding: 10px; 
}
###
```
Scoped css will only be applied within the context it is declared in. Unscoped css will be applied globally.
Conventionally, style comment blocks are placed at the bottom of the file. To see examples of how to style your imba pages check out the [building-a-beautiful-form tutorial](https://docs.imba.io/tutorials/building-a-beautiful-form) 
## inline styling
Imba also supports inline styling
> 🎮  [Play with this code on Scrimba](https://scrimba.com/c/cKpJRvTg)
