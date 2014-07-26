Banner
=====

[Hondo](https://github.com/amoose/hondo)'s trusty sidekick.

Based on the Ruby/Sinatra BitTorrent Tracker by [shurikk](https://github.com/shurikk/bttrack). 

Simple [BitTorrent](http://bittorrent.org/) tracker using [Sinatra](http://www.sinatrarb.com/) that doesn't require database backend

Implemented: [BEP 3](http://bittorrent.org/beps/bep_0003.html), [BEP 23](http://bittorrent.org/beps/bep_0023.html)


Roadmap
--------

[shurikk](https://github.com/shurikk/bttrack) created a simple and beautiful bittorrent tracker with 
infinite possibily. Banner will include a simple authorization layer for authenticating
with the Hondo API. 

Installation
------------
 
running on localhost, port 8888, using rack

    $ git clone git://github.com/amoose/bttrack.git
    $ cd bttrack; bundle install
    $ bundle exec rackup -p 8888

or create a .torrent file and use http://bttrack.heroku.com/announce as announce URL


License
-------

Released under the MIT license.
