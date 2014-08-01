Install Rails
======

Install Rails is a script to set up a Linux or Mac OS X system for Rails development.

Requirements
------------

### Linux

Currently supports Ubuntu, Linux Mint and other Debian based distributions.

### Mac OS X

Install a C compiler:

For Snow Leopard (10.6): use [OS X GCC
Installer](https://github.com/kennethreitz/osx-gcc-installer/).

For Lion (10.7) or Mountain Lion (10.8): use [Command Line Tools for
XCode](https://developer.apple.com/downloads/index.action).

For Mavericks (10.9): run `sudo xcodebuild -license` and follow the instructions
to accept the XCode agreement.  Then run `xcode-select --install` in your
terminal and then click "Install".

Install
-------

### Linux

Run the script:

    bash <(wget -qO- https://raw.githubusercontent.com/techAPJ/install-rails/master/linux)

### Mac OS X

Run the script:

    bash <(curl -s https://raw.githubusercontent.com/techAPJ/install-rails/master/mac)

What it sets up
---------------

* [Git][git_link]
* [rbenv][rbenv_link]
* [ruby-build][ruby_build_link]
* [Ruby][ruby_link] (stable)
* [Rails][rails_link]
* [PostgreSQL][pg_link]
* [SQLite][sqlite_link]
* [Redis][redis_link]
* [Bundler][bundler_link]
* [ImageMagick][imagemagick_link]

It should take less than 15 minutes to install (depends on your machine).

Credits
-------

Inspired by [Thoughtbot Laptop](https://github.com/thoughtbot/laptop).

License
-------

Install Rails is released under the [MIT License](http://www.opensource.org/licenses/MIT).



[git_link]: http://git-scm.com/
[rbenv_link]: https://github.com/sstephenson/rbenv
[ruby_build_link]: https://github.com/sstephenson/ruby-build
[ruby_link]: https://www.ruby-lang.org/
[rails_link]: http://rubyonrails.org/
[pg_link]: http://www.postgresql.org/
[sqlite_link]: https://sqlite.org/
[redis_link]: http://redis.io/
[bundler_link]: http://bundler.io/
[imagemagick_link]: http://www.imagemagick.org/
