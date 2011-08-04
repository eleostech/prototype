                     _               _                     
     _ __  _ __ ___ | |_  ___  _ __ | | __ _ ___ _ __ ___  
    | '_ \| '__/ _ \| __|/ _ \| '_ \| |/ _` / __| '_ ` _ \ 
    | |_) | | | (_) | |_| (_) | |_) | | (_| \__ \ | | | | |
    | .__/|_|  \___/ \__|\___/| .__/|_|\__,_|___/_| |_| |_|
    |_|                       |_|                          

=========

#### An object-oriented JavaScript framework ####

Protoplasm is Prototype with less:

  * Global stuff
  * DOM and AJAX (i.e., none, leaving you to choose a maintained framework)
  * Evolved-ness
  
and more:

  * Hardcore language features
  * Gooey fluid

### Building Protoplasm from source ###

`protoplasm.js` is a composite file generated from many source files in 
the `src/` directory. To build Protoplasm, you'll need:

* a copy of the Prototype source tree, either from a distribution tarball or
  from the Git repository (see below)
* Ruby 1.8.2 or higher (<http://www.ruby-lang.org/>)
* Rake--Ruby Make (<http://rake.rubyforge.org/>)
* RDoc, if your Ruby distribution does not include it

From the root Protoplasm directory,

* `rake dist` will preprocess the Protoplasm source using Sprockets and 
  generate the composite `dist/protoplasm.js`.
* `rake package` will create a distribution tarball in the 
  `pkg/` directory.

Contributing to Protoplasm
-------------------------

Check out the Protoplasm source with 

    $ git clone git://github.com/eleostech/prototype.git
    $ cd prototype
    $ git submodule init
    $ git submodule update vendor/sprockets vendor/pdoc vendor/unittest_js

Documentation
-------------

For the time being you can use the language bits from Prototype's API: <http://api.prototypejs.org>.