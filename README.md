# Tell Stories with Slides

Have you ever used Powerpoint or Keynote to make a presentation? If you
haven't yet, you probably will someday soon. 

A presentation is simple, words on a blank page, pictures, and
transitions. Like a deck of cards you show to your audience to help you
tell a story. The best presentations are fun and easy to understand.
They combine words and pictures that go with the story you are telling.

## Today's Lesson

HTML is the language of code that lies behind nearly everything you see
on the Web today. From Facebook to Minecraft to the White House
homepage, HTML makes the words, pictures, and videos and CSS makes the shape, color, and
style of the Web. We'll be learning the basics of HTML and CSS, and
using those tools to write our own stories using a free and open source
framework called Slides. Brian Cavalier put it 

## Get Started

1. Clone this repository using Github for Windows or Mac, or Download
   the Zip.
2. Unzip the file that is downloaded in a folder you use for working on
   projects.
3. Double-click the index.html file or open it in a web browser. You'll
   see the first page of the story
4. Go back to the folder. There is another folder inside called
   'slides.' Open that and then open the slides.html file in a text
editor like Notepad++.
5. Fill in the blanks, copy slides to make new ones, and experiment!

## Challenges

* Copy some of the slides and make the deck longer.
* Change the background and text colors by editing the CSS
* Change a picture
* Add more pictures to expand the story

#deck.js

A JavaScript library for building modern HTML presentations. deck.js is flexible enough to let advanced CSS and JavaScript authors craft highly customized decks, but also provides templates and themes for the HTML novice to build a standard slideshow.

## Quick Start

This repository includes a `boilerplate.html` as a starting point, with all the extensions included. Just [download it](https://github.com/imakewebthings/deck.js/zipball/stable), open `boilerplate.html`, and start editing your slides.

## Documentation

Check out the [documentation page](http://imakewebthings.github.com/deck.js/docs) for more information on the methods, events, and options available in core and all the included extensions.  A sample standard slide deck is included in the package under the `introduction` folder.  You can also [view that sample deck](http://imakewebthings.github.com/deck.js/introduction) online to play with the available style and transition themes.

## Extensions, Themes, and Related Projects

Take a look at [the wiki](https://github.com/imakewebthings/deck.js/wiki) for lists of extensions, themes, and other related goodies.  If you have a publicly available project of your own, feel free to add to the list.

## Dependencies (included in this repository)

- [jQuery](http://jquery.com)
- [Modernizr](http://modernizr.com)

## Tests & Support

Unit tests are written with [Jasmine](http://pivotal.github.com/jasmine/) and [jasmine-jquery](https://github.com/velesin/jasmine-jquery). You can [run them here](http://imakewebthings.github.com/deck.js/test).

deck.js has been tested with jQuery 1.6+ and works in IE7+, Chrome, FF, Safari, and Opera. The more capable browsers receive greater enhancements, but a basic cutaway slideshow will work for all browsers listed above. Please don't give your presentations in IE6.

For any questions or general discussion about deck.js please direct your attention to the [mailing list](http://groups.google.com/group/deckjs) (uses Google groups.)  If you would like to report a bug, please see the [issues page](https://github.com/imakewebthings/deck.js/issues).

## Known Bug(s)

There is an issue with certain builds of Chrome that result in a solid blue background and generally broken decks.  This is a bug in Chrome ([Issue 91518](http://code.google.com/p/chromium/issues/detail?id=91518)) that stems from hardware acceleration of 3d transforms.  Current workarounds:

- Use a different browser. This problem doesn't exist in Safari, FF, Opera.
- Disable hardware compositing by setting `--disable-accelerated-compositing` in the Chrome loading options
- Replace instances of `translate3d` with `translate` in the CSS of your decks (though this will slow down performance on iOS devices and Safari.)

Firefox contains a bug that allows users to scroll horizontally using the trackpad despite `overflow-x:hidden`. ([Bug 664275](https://bugzilla.mozilla.org/show_bug.cgi?id=664275) and [Bug 325942](https://bugzilla.mozilla.org/show_bug.cgi?id=325942).) If anyone knows of any workarounds to this issue please contact me.

## Printing

Core includes stripped down black and white print styles for the standard slide template that is suitable for handouts.

## Awesome Contributors

- [jbuck](https://github.com/jbuck)
- [cykod](https://github.com/cykod)
- [dougireton](https://github.com/dougireton)
- [awirick](https://github.com/awirick)
- Daniel Knittl-Frank
- [alexch](https://github.com/alexch)

If you would like to contribute a patch to deck.js please do as much as you can of the following:

- Add or amend Jasmine tests.
- Add inline documentation.
- If the standard snippet of an extension changes, please change it in both the introduction deck and the snippet html in the extension folder.
- If the API changes, it would be awesome to receive a parallel pull request to the gh-pages branch which updates the public-facing documentation.

## License

Copyright (c) 2011-2012 Caleb Troughton

Dual licensed under the [MIT license](https://github.com/imakewebthings/deck.js/blob/master/MIT-license.txt) and [GPL license](https://github.com/imakewebthings/deck.js/blob/master/GPL-license.txt).
