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

* Addition of `<title>` element
* Proper use of semantic HTML
    * Added `<header>` element, complete with included `<nav>` element
    * Added `<main>` element
    * Replaced nonsemantic `<div>` elements with `<section>`
    * Wrapped images in `<figure>`
    * Added `<footer>` element
* Logical ordering of content within both the Service and Benefit subsections
* Proper numbering for header elements
* Images with alternate descriptors
* Extensive use of CSS positioning properties, such as `float`, `display`, and `position`, to display content


## Technologies Used

* HTML
* CSS


## Future Work

Future work on this project would likely come in the form of improved accessibility, partucularly for users with small screen sizes. The basic layout of the webpage is not stable when squeezed into small sizes, and a few visual elements are too indistinct even for nonimpared users to notice. The Benefits section in particular would benefit from the use of flexboxes.


## License

© 2022 John Netzel. All Rights Reserved.