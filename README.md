Railsgun
========

How to shoot a fly with a cannon - or take a sledgehammer to crack a nut.

Railsgun is a "pico" framework Rails based for creating quick and simple static websites.

That's a rushed release :)

Features
--------
* hierarchy organized pages via yaml conf file
* multilanguage site - like yoursite.com/it/pagine-italiane and yoursite.com/en/english-pages
* pretty urls
* built with Ruby on Rails
* UJS (unobtrusive javascript) ready
* Heroku ready
* Integrated AWS S3/Cloudfront assets deployment
* Caching
	
To-do
-----
* a lot of documentation
* a lot of tests

Raquirements:
-------------
* Ruby 1.8.7 or 1.9.2
* Rails 3.0.5
* Some gems - check Gemfile

Installation
------------

1. run `git clone https://github.com/cantierecreativo/railsgun.git`
2. run `gem install rails bundler`
3. run `cd railsgun`
4. edit `config/database.yml` according to your configuration
5. run `bundle install`
6. run `rake db:reset`
7. run `rake pages_tree:generate`

Usage
-----
* Generate pages tree via `db/pages_tree.yml` and then run `rake pages_tree:generate`
* Fill layouts and views partials
		
Credits
-------
Funded and developed by [Cantiere Creativo](http://www.cantierecreativo.net)

All the credits to the respective owners/devopers of gems/plugins/scripts used.

Contributors
------------
* [Silvio Relli](http://www.relli.org) - project manager and main coder
* [Matteo Papadopoulos](http://www.basictrading.biz) - logo and default theme designer
	