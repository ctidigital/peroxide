 Peroxide
=============

Peroxide is a Drupal theme engine allowing templates to be created using Haml
and stylesheets to be written using Sass and Scss.

Templates and styles for large sites can become quite long and complex.  The goal of this
project is to make more advanced tools available to developers so that the code for themes
is shorter, easier to understand and more maintainable.

Peroxide automatically compiles and caches templates as PHP. Sass and Scss files are also
automatically compiled, cached and their resultant output css is automatically added to a page.

Alongside of peroxide, a kickstarter theme is being developed to make getting started
easier.  It can be found at <https://github.com/codeincarnate/peroxide_theme>

Installation
------------

To install peroxide you can use the following commands starting from the root
of your Drupal installaiton:

	cd sites/all/themes (or whatever your theme directory is)
	mkdir engines
	cd engines
	git clone --recursive git://github.com/codeincarnate/peroxide.git

_Note_: For peroxide to work properly your Drupal site's files directory must be writable by your webserver.

Usage
------------

To use peroxide as the engine for your theme add this line  to your
themes info file.

	engine = peroxide

Basic Theme
------------

A basic theme using the peroxide theme engine can be found at <https://github.com/codeincarnate/oxygen>

Future
------------

Drupal forms are ugly!  Fortunately there are great creative commons licensed
graphics out there to use.  Ace (from Sproutcore) and Aristo (from Cappuccino)
both look great.  If someone would like to plug either of these in that would be awesome.
See this [article](http://www.antipode.ca/2009/themes-sproutcore-vs-cappuccino/) for more
information.

License
------------

Peroxide is made available under the terms of the GPLv2.  For the full
text of this license see <http://www.gnu.org/licenses/gpl-2.0.html>


Credits
------------

Peroxide uses the phamlp library to parse HAML and Sass.  This can be found at
<http://code.google.com/p/phamlp/>

phamlp includes compass which can be found at <http://compass-style.org/>
