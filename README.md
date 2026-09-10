
vichan-next - A lightweight and full featured PHP imageboard.
========================================================

As of 29 August 2022 it supports PHP8.1.

About
------------
vichan-next is a free light-weight, fast, highly configurable and user-friendly
imageboard software package. It is written in PHP and has few dependencies.

History
------------
vichan-next is a fork of [Tinyboard](http://github.com/savetheinternet/Tinyboard),
a great imageboard package.

Requirements
------------
1.	PHP >= 7.4
2.	MySQL/MariaDB server
3.	[mbstring](http://www.php.net/manual/en/mbstring.installation.php)
4.	[PHP GD](http://www.php.net/manual/en/intro.image.php)
5.	[PHP PDO](http://www.php.net/manual/en/intro.pdo.php)
6.	A Unix-like OS, preferrably FreeBSD or GNU/Linux

We try to make sure vichan-next is compatible with all major web servers. vichan-next does not include an Apache `.htaccess` file nor does it need one.

### Recommended
1.	MySQL/MariaDB server >= 5.5.3
2.	ImageMagick (command-line ImageMagick or GraphicsMagick preferred).
3.	[APCu (Alternative PHP Cache)](http://php.net/manual/en/book.apcu.php),
	[Memcached](http://www.php.net/manual/en/intro.memcached.php) or
	[Redis](https://redis.io/docs/about/)

Contributing
------------
You can contribute to vichan-next by:
*	Developing patches/improvements/translations and using GitHub to submit pull requests
*	Providing feedback and suggestions
*	Writing/editing documentation

Installation
-------------
1.	Get the latest development version with:

        git clone https://github.com/BubblySovereign/vichan-next-next.git

2.	run ```composer install``` inside the directory
3.	Navigate to ```install.php``` in your web browser and follow the
	prompts.
4.	vichan-next should now be installed. Log in to ```mod.php``` with the
	default username and password combination: **admin / password**.

Please remember to change the administrator account password.
