# RackStep

RackStep is (yet another) micro ruby framework for microservices and web development.

Main goals are:
- be as simple as possible.
- keep the source code small.
- implement only the necessary; no overcomplication.
- allow easy implementation of microservices and single-page application (SPA).
- use a pure object oriented approach, avoiding DSLs  and configuration files.


## Status
[![Gem Version](https://badge.fury.io/rb/rackstep.svg)](https://badge.fury.io/rb/rackstep)
[![Travis CI](https://api.travis-ci.org/mfdavid/rackstep.svg)](https://travis-ci.org/mfdavid/rackstep)
[![Code Climate](https://codeclimate.com/github/mfdavid/rackstep/badges/gpa.svg)](https://codeclimate.com/github/mfdavid/rackstep)
[![Ich CI](http://inch-ci.org/github/mfdavid/rackstep.png)](http://inch-ci.org/github/mfdavid/rackstep)
[![Gemnasium](https://gemnasium.com/mfdavid/rackstep.svg)](https://gemnasium.com/mfdavid/rackstep)


## Dependancies

RackStep is developed and tested with Ruby 2.2.3. The only hard dependency is
Rack itself, but there are a few others recommended gem dependancies:
- unicorn: fast rack-compatible server that can be used for production.
- simplecov: a simple way to generate statistics about your unit tests coverage.


## How to use RackStep

Make sure you have ruby 2.2.3 installed (ruby --version). If you don't, we recomend you to use [rbenv](https://github.com/sstephenson/rbenv#installation) to install it.

Install the bundle gem if you don't have it already: gem install bundle

To create a new application, you may clone one of the following repositories as a starting point example:

A full app example:
https://github.com/mfdavid/rackstep-app-template

A minimum app example:
https://github.com/mfdavid/rackstep-minimum-app-template

Go into the directory you cloned the project and install the dependancies by running: bundle install

Start the application server using any rack-compatible server. For development I recommend using shotgun or rackup. For production, RackStep full app example is pre-configured to use unicorn.


## In the wild (who is using it?)

RackStep is still in very early stage of development and testing. Right now there is only one website that was build using it: [Ninirc.com](http://ninirc.com)


## TODOs (some of them)

- use RDoc or YARD for documentation.
- create more tests.
- add some performance tests and do some optimizations.
- solve all the TODOs listed around the source code.


## Author

RackStep is developed by Marcio Frayze David - mfdavid@gmail.com.
