# Structure Web Pages in HTML
## Process and Design
* Consider the site's target demographic
* Think of visitor's motivation and goals, and how often they will visit
#### Vocabulary
* site map - shows how pages are grouped
* card sorting - place info on separate papers and orgnize into groups
* wireframe - a sketch of key info on each page of a site
* visual hierarchy - draws atttention to key messages then guides to subsequent messages using size, color, and style
* Design Navigation Principles - Concise, clear, selective, context, interactive, consistent

## HTML and CSS
* attributes - Appear in the opening tag and consist of a name and a value, such as `<p lang="en-us">`
* `<body>` - everything inside is shown in the media browser window
* `<head>` - info about th page
* `<title>` - Shown above the URL or in the tab

## HTML5 Layout
* `<article>` - For a section of a page that can stand alone
* `<aside>` - Can contain unessential info related to an article, or act as a container for content related to the entire page
* `<section>` - Groups related content togeher
* `<hgroup>` - Can contain a heading and a subheading
* `<figure>` - Has content related to an article such as an image or graph
* For these elements, add a CSS line that says they should be treated as blocks to help older browsers

## Extra Markup
* Start each page with `<!DOCTYPE html>`
* `<--...-->` - comment
* You can use an id element to give one element a unique style: `<p id="pull quote">`
* A class can change several elements
* Inline elements - Appear on the same line as neighbouring elements 
* `<span>` - In line equivalent of `<div>`
* `<iframe>` - A window in your page that can show another page
* `<meta>` - In `<head>` where it will help with search engine results
* Escape Characters - A way to write characters that are reserved by HTML code