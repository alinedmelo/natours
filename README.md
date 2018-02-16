# Natours
Project from the advanced css course - Jonas Schmedtman

## Preview 

https://alinedmelo.github.io/natours/

### Notes 

#### Sources order of the stylesheets

1. Author - Is the CSS we write and apply to our pages
2. User - CSS of the user device (when the user changes the font-size of the bowser, for example)
3. Brownser (user agent) - the default styleshhet of the browser


**Importance > specificity > source order**

##### Importance
1. User !important declarations
2. Author !important declarations
3. Author declarations[
4. User declarations
5. Deafult browser  declarations

##### Specificity

1. inline styles
2. IDs
3. Classes, pseudo-classes, attribute
4. elements, pseudo-elements

##### Source Order

The last declarated file will be applied

