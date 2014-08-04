AEM Client Librarian clientlib Template
=======================================

[CITYTECH, Inc.](http://www.citytechinc.com/)

Overview
-------

An AEM Client Librarian clientlib Template.

Usage
-----

This template includes a blank CSS and JS file as well a directory structure for CSS, JS and image assets.

The js.txt and css.txt files should list the files the Client Librarian should use to build the clientlib in order.

Note that [LESS](http://lesscss.org/) files could live inside the css directory and be referenced in the css.txt file. If using LESS, it use .less extension for all of your files, even if they do not all use LESS features.

Additional directories for other assets (fonts, etc) could be created and would just need the .content.xml files found in the css and js directories.

Requirements
------------

This clientlib template has stubs for features of the [Client Librarian](https://github.com/Citytechinc/client-librarian), which extends the base functionality of AEM clientlibs. See the [Client Librarian project](https://github.com/Citytechinc/client-librarian) for more information.
