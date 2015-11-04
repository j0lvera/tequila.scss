Tequila.scss
========

A SCSS mixing that creates small, simple and useful fluid grid systems.

The last three years of freelancing I got several issues using other grids, not because they were bad, instead because there is not one complete solution for every problem.

I came up with my own solution, a mixing function that can create a fluid grid with the column sizes I need, only that, other customization to the grid can be done with the project requirements.

Tequila.scss philosophy resides on Doug McIlroy's famous summation of the Unix philosophy:

> Write programs that do one thing and do it well. Write programs to work together. Write programs to handle text streams, because that is a universal interface.

Easy it is to use:

```bash
$ bower install tequila.scss
```

```scss
@import 'tequila';

// Settings
$gutter: 3%;
@include namespace('col-');

.col-1-2 {
  @include fraction(1/2);
}

sidebar {
  @include cols(4, 0);
}
```

Features and goals
------------------

- Flexibility between keep your DOM clean and semantic or use a more OOCSS-ish approach in your projects.
- Have a flexible gutter size: you can change it whenever you want and your grid won't break.
- Be small, simple, fast and useful.
- Mantain a powerful and easy to understand syntax, `.cols(1/3);` for one column of three, and `.cols(8);` for one element with the size of eight columns.
- Get only what you need, this tool is designed to build a grid ad-hoc to your project. You are not stuck with a rigid API.
- You will get an extensible/hackeable result, Tequila.scss won't try to do all the work, you get a fluid grid system that you can modify any way you want.

Installation
------------

Install tequila.scss by running:

```bash
  bower install tequila.scss
```

Contribute
----------

- Issue Tracker: http://github.com/thinkxl/tequila.scss/issues
- Source Code: http://github.com/thinkxl/tequila.scss/

Credits and Thanks
------------------

- Special thanks to [@Snugug](https://twitter.com/Snugug), helped me to understand how grids works and suggested a better implementation of this project.
- `##frontend` IRC channel, because they help me every time I ask a dumb questions.

License
-------

The project is licensed under the MIT license.
