# Intro to CSS #
- Cascading Style Sheet 

A CSS rule contains two parts: **selector** and **declaration**

Ex: `p {font-family: arial;}` P being the selector and "{font-family: arial;}" as selector

Inside the curly brackets has two parts - **property** and **value** ,*font-family* being the property and *arial* being the value

`<link>` 
- is used in an HTML doc to tell th browser where to find the CSS file used to style page.
- lives inside the `<head>` element
- should use these three attribute
  1. href - specifies path to the CSS file
  1. type - specifies the type of doc being l
  1. rel - specifoes relationship between HTML page and file it is linked to. 

`<style>`
 - usually sits inside the `<head>` element of the page

 When building more than one page, you should use an external CSS style sheet.

 **CSS selectors**
 Allows you to target rules to specific elements in HTML
 - CASE SENSITIVE , element names and attribute values need to match


# Color #

**Text Color**
`color` property allows you to specify the color of the text inside an element.

- RBG values ex: `rgb (100,100,90)`. expresses how much red, green, blue to use

- Hex codes ex: `#ee3e80`

- There are 147 colors names as well. 

**Background color**
- CSS treats HTML as it appears in a *box*
- you can change the background-color the same way you change text color

# CSS3 #

**Opasity**
Allows you to specify the opasity of an element andany of its child elements
- value is between 0.0 - 1.0

**rgba**
Allows you to specify a color like RGB but as a fourth value to indicate opacity
- value is between 0.0 - 1.0
- only affects the element on which it is applied, not child elements

Some browsers may not recognize RGBA colors. Fallback is to display solid colors. If there are two rules that apply to the same element, the latter will take priority. To *create* the fallback, yu can specify a color as a hex code, color name, or rgb value

**HSL**
Alternative way to specify colors

**HSLA**
Allows you to specify color properties using hue, saturationm and lightness, and adds a fourth value which represents transparency.





