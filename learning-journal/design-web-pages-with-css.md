# Design Web Pages with CSS
## Introducting CSS
* CSS properties affect how elements are displayed
* CSS can be linked in to HTML in the head (exernal CSS) or can be
 used in the `<style>` section (internal CSS)
 * There are a variety of CSS selectors, such as universal, type, class,
 or ID
 * If yo specify a font-family or color property,
 child elements will have that property

 ## Color
 * There are 3 ways to specify color
   * RGB Values: `rgb(100, 100, 90)` pick a number 0-255 for red, green, then blue
   * Hex codes: '#ee3e80' pick the hexadecimal number for red, green, and blue
   * Color Names: 147 predefined colors
* `background-color` fills in the box of HTML specified
* Hue - color
* Saturation - amount of gray in a color
* Brightness - how much black is in a color
* Ensure there is contrast for text to be legible over a background
* For long spans of text, medium contrast is best
* Opacity is measured 0 - 1
* `rgba(0,0,0,.1)` - 'a' means alpha, and represents opacity 
* HSL - Hue, Saturation, Lightness
  * Can also be HSLA
  * Hue - 0 - 360
  * Saturation - expressed as a percentage
  * Lightness: 0%(white) - 100%(black)
  * Alpha - 0-1 like rgba
  * Example: `hsla(0, 100%, 100%, .5)`
  
