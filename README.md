#Responsive_scss-master
Inspired by [Guilherme Pangnotta][1] a simpler way
#Plugins

- [Normalize.css][2] - A modern, HTML5-ready alternative to CSS resets.
- [jQuery][3] - A fast, small, and feature-rich JavaScript library.
- [jQuery Easing][4] - A jQuery plugin to give advanced easing options.
- [FitVids][5] - A lightweight, easy-to-use jQuery plugin for fluid width video embeds.
- [FullScreenBg][6] - A small jQuery plugin that allows you to create fullscreen background.
- [Modernizr][7] - JavaScript library that detects HTML5 and CSS3 features in the user’s browser.
- [Slider][8] - Simple and custom slide

#Structure

    ├── Responsive_scss-master/
    │   ├── css/
    │   │   ├── main.css             (sass output)
    │   │   └── normalize.css        (aplha male of css resets)
    │   ├── sass/
    │   │   ├── main.sass            (basic sass configuration and media queries)
    │   ├── img/
    │   │   └── loading.gif          (fake 'loading' background)
    │   └── js/
    │       ├── functions.js         
    │       ├── grid.js              
    │       ├── jquery.js            (jquery library)
    │       ├── modernizr.js         (html5 + css3 for the masses)
    │       └── plugins.js           
    └── index.html                   

#Using [Sass][9]

Install Sass

    gem install sass

Run Sass:

    sass sass/main.sass css/main.css

Compile with:

    sass --watch sass/main.sass:css/main.css

Compile with (compressed):

    sass --watch sass/main.sass:css/main.css --style compressed

#License

Responsive_scss-master is under a [Creative Commons Attribution License][10].


  [1]: https://github.com/setetres/sasstarter
  [2]: http://necolas.github.io/normalize.css/
  [3]: http://jquery.com/
  [4]: https://github.com/gdsmith/jquery.easing
  [5]: https://github.com/davatron5000/FitVids.js
  [6]: https://github.com/Gaya/Fullscreen-Background-jQuery-plugin
  [7]: https://github.com/Modernizr/Modernizr
  [8]: https://github.com/Raynner/touch-slider
  [9]: https://github.com/nex3/sass
  [10]: http://creativecommons.org/licenses/by/4.0/
