# [Responsive Portfolio](#project-title)

This project page is a demonstration of building a webpage using Bootstrap. The goal of the project was to recreate a site using client provided design as a guide. Maximizing the amount of Bootstrap classes while minimizing the amount of custom CSS was adopted as an additional learning challenge. 

## [Table of Contents](#toc)

[Responsive Portfolio](#project-title)

[Table of Contents](#toc)

[Goals and Methods](#goalsmethods)

[Technologies](#technologies)

[Deployed Link](#deployed-link)

[Authors](#authors)

[Acknowledgments](#acknowledgments)

[License](#license)

## [Goals and Methods](#goalsmethods)

The overarching goal of this project was to build a responsive website using client provided design parameters. As a learning challenge this build was completed using as mamy Bootstrap features as possible while mimnimizing the use of custom CSS. Site layout was adapted for three distinct viewing widths of 400 px, 768pz, and 900 px. This functionality was handled using Bootstrap's built-in grid system. A typical use of the Bootstrap class that made this functionality possible is shown in Snippet 1.
Snippet 1:
```HTML
    <figure class="col-sm-12 col-md-6">
        <img src="http://placehold.it/350x350" alt="Placeholder" class="img-fluid p-2"/>
        <img src="http://placehold.it/350x350" alt="Placeholder" class="img-fluid p-2"/>
        <img src="http://placehold.it/350x350" alt="Placeholder" class="img-fluid p-2"/>
    </figure>
    <figure class="col-sm-12 col-md-6">
        <img src="http://placehold.it/350x350" alt="Placeholder" class="img-fluid p-2"/>
        <img src="http://placehold.it/350x350" alt="Placeholder" class="img-fluid p-2"/>
    </figure>
```
This code when viewed in a screen size 768px or larger displays two columns of images. When viewed on screens smaller than 768 px the photos collapse into a single column. Bootstrap's class .container-fluid was reponsible for handling size scaling and layout changes inbetween screen size breakpoints. That class also made it possible to have two nav bar at the 768 px breakpoint (Figure 1 and Figure 2) by wrapping the entire navbar section in a .container-fluid.

Figure 1

![Figure 1](images/navbarlarge.png)

Figure 2

![Figure 2](images/navbarcondensed.png)


## [Technologies](#technologies) 

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* [Bootstrap 5](https://getbootstrap.com/)

## [Deployed Link](#deployed-link)

* [See Live Site](https://coleman-buffa.github.io/responsive-portfolio/index.html)

## [Authors](#authors)

Coleman Buffa

- [Link to Github](https://github.com/coleman-buffa/responsive-portfolio)
- [Link to LinkedIn](https://www.linkedin.com/in/coleman-buffa-0a12a5201/)

## [Acknowledgments](#acknowledgments)

* Many thanks to UCB Bootcamp Instruction Staff

## [License](#license)

* Bootstrap is released under the MIT license and is copyright 2020 Twitter

### [Return to TOC](#toc)


