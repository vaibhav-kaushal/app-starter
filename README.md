# QCubed Application Starter
This is the application starter project that sets up your environment using composer. 


REQUIREMENTS
------------

You must have a web server, like apache or nginx, installed and working on your computer.

You must have PHP version 5.4.0 or greater installed and working.

You must have some kind of SQL database. MySQL, PostreSQL, and many others are supported.

We highly recommend you also install Composer. Composer helps you manage version changes in all your different
PHP packages, and we rely on that to provide installation and update services for QCubed.


INSTALLATION
------------

### Install via Composer

If you do not have [Composer](http://getcomposer.org/), you may install it by following the instructions
at [getcomposer.org](http://getcomposer.org/doc/00-intro.md#installation-nix).

Once installed, you can install this app-starter project by executing the following at the command line:

~~~
php composer.phar create-project qcubed/app-starter your_dir_name
~~~

Substitute whatever directory name you would like for "your_dir_name" above. 

Note that if you have taken the step to rename "composer.phar" to "composer" and you put it in your path, you can instead
just enter:

~~~
composer create-project qcubed/app-starter your_dir_name
~~~

Assuming you installed into the document root of your local web server, enter the following to begin the 
configuration process.

~~~
http://localhost/your_dir_name/
~~~

If you would like to eventually place the project somewhere else in your webserver tree, even at the root level, it is
easy to do by modifying the __SUBDIRECTORY__ configuration file setting and moving the contents of the directory to the
new location.
