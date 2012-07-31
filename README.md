Laptop
======

Laptop is a script to set up your Max OS X laptop as a web development machine.

Requirements
------------

* A C compiler, such as GCC, LLVM, or Clang.
* [X11](http://xquartz.macosforge.org/trac/wiki)
* [MySQL](http://www.mysql.com/downloads/mysql/)

Download a compiler from [OS X GCC Installer](https://github.com/kennethreitz/osx-gcc-installer/) if you're on Snow Leopard (OS X 10.6) or [Command Line Tools for XCode](https://developer.apple.com/downloads/index.action) if you're on Lion (OS X 10.7). Mountlion Lion
users can download the [Command Line Tools for Mountain Lion](http://adcdownload.apple.com/ios/ios_simulator__resigned/cltools_mountainliondp2_march12.dmg)


Install
-------

Run the script:

    curl -s https://raw.github.com/bryanmtl/laptop/master/mac | sh


What it sets up
---------------

* SSH public key (for authenticating with services like Github and Heroku)
* Homebrew (for managing operating system libraries)
* Git
* Git Flow
* Ack (for finding things in files)
* ImageMagick (for cropping and resizing images)
* RVM (for managing versions of the Ruby programming language)
* Ruby language (for writing general-purpose code)
* Bunch of commonly used gems (Sass, Compass, Stitch etc...)
* Coffeescript


It should take about 30 minutes for everything to install, depending on your machine.

