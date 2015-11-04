Tequila.scss
========

A SCSS mixing that creates small, simple and useful fluid grid systems.

The last three years of freelancing I got several issues using other grids, not because they were bad, instead because there is not one complete solution for every problem.

I came up with my own solution, a mixing function that can create a fluid grid with the column sizes I need, only that, other customization to the grid can be done with the project requirements.

Tequila.scss philosophy resides on Doug McIlroy's famous summation of the Unix philosophy:

> Write programs that do one thing and do it well. Write programs to work together. Write programs to handle text streams, because that is a universal interface.

Goals
-----

* Keep your DOM clean and semantic
* Have a flexible gutter size: you can change it whenever you want and your grid won't break.
* Be small, simple, fast and useful, take a look on the list of websites using it.
* Mantain a powerful and easy to understand syntax, .cols(1/3); means one column of three, .cols(8); means one element with the size of eight columns.
* Get only what you need, this tool is designed to build a grid ad-hoc to your needs. You are not stuck with a rigit API or only one way to build your grid.
* You will get an extensible/hackeable result, hyx.less won't try to do all the work, you get a fluid grid system that you can use the way you want.

Easy it is to use:

  $ bower install tequila.scss

  ```scss
  .col-1-2 {
    @include fraction(1/2);
  }

  sidebar {
    @include cols(4, 0);
  }
  ```

Features
--------

- Be awesome
- Make things faster

Installation
------------

Install tequila.scss by running:

  bower install tequila.scss

Contribute
----------

- Issue Tracker: github.com/thinkxl/tequila.scss/issues
- Source Code: github.com/thinkxl/tequila.scss/

Credits and Thanks
------------------

- Special thanks to [@Snugug](https://twitter.com/Snugug), helped me to understand how grids works and suggested a better implementation of this project.
- `##frontend` IRC channel, because they help me every time I ask a dumb questions.

License
-------

The project is licensed under the MIT license.
