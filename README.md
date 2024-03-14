# Open Publication Design (OPD)

Resources for multi-format publication design

Covering the use of:

  - Multi-format outputting from Fidus Writer
  - CSS Typesetting with Vivliostyle
  - Github and GitLab Pages design with Docsify
  - Computational Publication design with Quarto
  - Git based publishing workflows
  
See the Wiki for documentationn and instructions: https://github.com/a-machine/opd/wiki  

## Examples

### Page style change by using page number counter: Use :nth()

W3C guidance: Selecting Pages - https://www.w3.org/TR/css-gcpm-3/#the-first-page-pseudo-element

This allows you to make a style for page 6, here it's just a blue background. Add this to your CSS.

See example Vivliostyle render [page 6 here](https://vivliostyle.vercel.app/#src=https://raw.githubusercontent.com/a-machine/open-publication-design/main/vivlio/examples/colophon/index.html&f=epubcfi(/2!/4/10[_1_0])) and [CSS code here](https://github.com/a-machine/open-publication-design/blob/110fddbf48cde2b1552e5e99cf48c1be09fb19e8/vivlio/examples/colophon/css/book-gaffm-en.css#L150).

`@page:nth(6) {`

  `background: blue;`
  
`}`
