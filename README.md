# My Portfolio

## Introduction 

This is a personal project of mine, undertaken with an eye towards potential employers. I created this webpage to showcase my ability to create a basic, single-page website from scratch. In addition to serving as a brief introduction to other projects of mine, this webpage demonstrates my ability to use and include modern features such as semantic HTML and CSS media queries in a website.

![Screenshot of final product.](https://github.com/CommieDog/my-portfolio/blob/main/assets/images/readme/my-portfolio-website-screenshot.jpg)

A sample deployment of the website is available on [GitHub Pages](https://commiedog.github.io/my-portfolio/).


## Table of Contents

* [Description](#description)
* [Features](#features)
* [Technologies Used](#technologies-used)
* [Future Work](#future-work)
* [License](#license)


## Description

### Design

This webpage was designed first by wireframe in a drawing program. The webpage consists of a header with my name, photo, address. and a navbar with links to the other sections. The fist section in the main body is a brief biography. The next, and largest, section is a curation of projects that I created or contributed to. After that are sections listing my knowedge base and contact information. At the end is a footer with copyright information.

![Screenshot of page wireframe.](https://github.com/CommieDog/my-portfolio/blob/main/assets/images/readme/my-portfolio-wireframe.jpg)

### Layout

The header of the website is split into two columns, the left column with my name and portrait and the right column with my address and the site navbar. The header's background is a darker shade of blue to help it stand out from the rest of the page. On small screens, the columns are displayed as rows instead.

While most of the sections are simple paragraphs or lists, the project showcase has a much more complex design. Projects are represented as "tiles" consisting of a name caption, an image, and a brief description that appears when the tile is hovered over. The first project in the section is displayed extra large for emphasis.

How the projects are laid out on the screen is heavily dependent on the screen's width, which is used to infer the type of device that is being used to browse the page. On desktop and laptop monitors, the showcase uses a grid layout with three columns, and the first project is positioned to occupy two rows and two columns. On tablet screens, the layout is simplified to a flexbox wide enough to accomodate the first project on the first row and two other projects on subsequent rows. On smartphone screens, the showcase uses a simple block layout.

Currently, most of the project tiles are placeholders. Only the first project features work of mine.


## Features

* Proper use of semantic HTML
* Responsive web design
* Multiple stylesheets
* Rich use of CSS features
  * Linear gradient background
  * Pseudo-classes such as `:hover`
  * Variables
  * Media queries
* CSS functions
    ```CSS
    .project:first-child {
      width: calc(var(--project-item-width) * var(--project-first-size-mult));
      ...
    }
* Extensive use of CSS `display` properties, including `flex` and `grid`, to display content


## Technologies Used

* HTML
* CSS


## Future Work

The biggest improvement for this website would be to have some projects for me to display instead of having to use placeholders. The biography section could also use a rewrite; I'm not terribly good talking about myself.


## Credits

[Normalize.css](https://github.com/necolas/normalize.css) Copyright © Nicolas Gallagher and Jonathan Neal

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


## License

© 2022 John Netzel. All Rights Reserved.