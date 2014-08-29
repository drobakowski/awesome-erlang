# Awesome Erlang
A curated list of amazingly awesome Erlang libraries, resources and shiny thing inspired by [awesome-elixir](https://github.com/h4cc/awesome-elixir).

- [Awesome Erlang](#awesome-Erlang)
    - [Package Management](#package-management)
    - [Release Management](#release-management)
    - [Web Frameworks](#web-frameworks)
    - [Web Framework Components](#web-framework-components)
    - [HTTP](#http)
    - [Testing](#testing)
    - [Logging](#logging)
    - [Monitoring](#monitoring)
    - [Code Analysis](#code-analysis)
    - [Build Tools](#build-tools)
    - [Geolocation](#geolocation)
    - [Debugging](#debugging)
    - [Actors](#actors)
    - [Date and Time](#date-and-time)
    - [ORM and Datamapping](#orm-and-datamapping)
    - [Queue](#queue)
    - [Authentication](#authentication)
    - [Text and Numbers](#text-and-numbers)
    - [REST and API](#rest-and-api)
    - [Caching](#caching)
    - [Third Party APIs](#third-party-apis)
    - [Networking](#networking)
    - [Algorithms and Datastructures](#algorithms-and-datastructures)
    - [Translations and Internationalizations](#translations-and-internationalizations)
    - [Miscellaneous](#miscellaneous)
- [Resources](#resources)
    - [Websites](#websites)
    - [Books](#books)
    - [Web Reading](#web-reading)
    - [Erlang Reading](#Erlang-reading)
    - [Screencasts](#screencasts)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

## Package Management
*Libraries and tools for package and dependency management.*

## Release Management
*Libraries and tools for release management.*

* [relx](https://github.com/erlware/relx) - A release assembler for Erlang.

## Web Frameworks
*Web development frameworks.*

* [Axiom](https://github.com/tsujigiri/axiom) - A micro-framework, inspired by Ruby's [Sinatra](https://github.com/sinatra/sinatra).
* [ChicagoBoss](https://github.com/ChicagoBoss/ChicagoBoss) - A server framework inspired by Rails and written in Erlang.
* [cowboy](https://github.com/extend/cowboy) - A simple HTTP server.
* [Giallo](https://github.com/kivra/giallo) - A small and flexible web framework on top of [Cowboy](https://github.com/extend/cowboy).
* [MochiWeb](https://github.com/mochi/mochiweb) - An Erlang library for building lightweight HTTP servers.

## Web Framework Components
*Standalone component from web development frameworks.*

* [cb_admin](https://github.com/ChicagoBoss/cb_admin) - An admin interface for Chicago Boss.
* [cb_websocket_controller](https://github.com/dkuhlman/cb_websocket_controller) - A template for implementing a Websocket controller for ChicagoBoss.
* [giallo_session](https://github.com/kivra/giallo_session) - A session management library for the Giallo web framework.

## HTTP
*Libraries for working with HTTP and scraping websites.*

* [lhttpc](https://github.com/esl/lhttpc) - A lightweight HTTP/1.1 client implemented in Erlang.

## Testing
*Libraries for testing codebases and generating test data.*

* [PropEr](https://github.com/manopapad/proper) - A QuickCheck-inspired property-based testing tool for Erlang.

## Logging
*Libraries for generating and working with log files.*

* [lager](https://github.com/basho/lager) - A logging framework for Erlang/OTP.
* [lager_amqp_backend](https://github.com/jbrisbin/lager_amqp_backend) - AMQP RabbitMQ Lager backend.
* [lager_hipchat](https://github.com/synlay/lager_hipchat) - HipChat backend for lager.
* [lager_loggly](https://github.com/kivra/lager_loggly) - Loggly backend for lager.
* [lager_smtp](https://github.com/blinkov/lager_smtp) - SMTP backend for lager.
* [logplex](https://github.com/heroku/logplex) - Heroku log router.

## Monitoring
*Libraries for gathering metrics and monitoring.*

* [entop](https://github.com/mazenharake/entop) - A top-like Erlang node monitoring tool.
* [eper](https://github.com/massemanet/eper) - A loose collection of Erlang Performance related tools.
* [Exometer](https://github.com/Feuerlabs/exometer) - An Erlang instrumentation package.
* [folsom](https://github.com/boundary/folsom) - An Erlang based metrics system inspired by Coda Hale's [metrics](https://github.com/codahale/metrics).
* [statsderl](https://github.com/lpgauth/statsderl) - A statsd Erlang client.
* [vmstats](https://github.com/ferd/vmstats) - Tiny Erlang app that works in conjunction with statsderl in order to generate information on the Erlang VM for graphite logs.

## Code Analysis
*Libraries and tools for analysing, parsing and manipulation codebases.*

* [eflame](https://github.com/proger/eflame) - A Flame Graph profiler for Erlang.

## Build Tools
*Project build and automation tools.*

* [rebar](https://github.com/rebar/rebar) - Erlang build tool that makes it easy to compile and test Erlang applications, port drivers and releases.

## Geolocation
*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [erl-rstar](https://github.com/armon/erl-rstar) - An Erlang implementation of the R*-tree spacial data structure.
* [GeoCouch](https://github.com/couchbase/geocouch) - A spatial extension for Couchbase and Apache CouchDB.
* [Teles](https://github.com/armon/teles) - An Erlang network service for manipulating geographic data.

## Debugging
*Libraries and tools for debugging code and applications.*

## Actors
*Libraries and tools for working with actors and such.*

* [poolboy](https://github.com/devinus/poolboy) - A hunky Erlang worker pool factory.

## Date and Time
*Libraries for working with dates and times.*

## ORM and Datamapping
*Libraries that implement object-relational mapping or datamapping techniques.*

* [boss_db](https://github.com/ChicagoBoss/boss_db) - A sharded, caching, pooling, evented ORM for Erlang.

## Queue
*Libraries for working with event and task queues.*

* [tinymq](https://github.com/ChicagoBoss/tinymq) - A diminutive, in-memory message queue for Erlang.

## Authentication
*Libraries for implementing authentications schemes.*

* [oauth2](https://github.com/kivra/oauth2) - Erlang Oauth2 implementation.

## Text and Numbers
*Libraries for parsing and manipulating text and numbers.*

* [jsx](https://github.com/talentdeficit/jsx) - an erlang application for consuming, producing and manipulating json.

## REST and API
*Libraries and web tools for developing REST-ful APIs.*

* [leptus](https://github.com/s1n4/leptus) - Leptus is an Erlang REST framework that runs on top of cowboy.

## Caching
*Libraries for caching data.*

## Third Party APIs
*Libraries for accessing third party APIs.*

* [restc](https://github.com/kivra/restclient) - An Erlang REST client
* [oauth2c](https://github.com/kivra/oauth2_client) - An Erlang oAuth 2 client (uses restc)

## Networking
*Libraries and tools for using network related stuff.*

## Algorithms and Datastructures
*Libraries and implementations of algorithms and datastructures.*

* [erlando](https://github.com/travelping/erlando) - A set of syntax extensions like currying and monads for Erlang.
* [statebox](https://github.com/mochi/statebox) - Erlang state "monad" with merge/conflict-resolution capabilities.
* [riak_dt](https://github.com/basho/riak_dt) - Erlang library of state based CRDTs.

## Translations and Internationalizations
*Libraries providing translations or internationalizations.*

## Miscellaneous
*Useful libraries or tools that don't fit in the categories above.*

# Resources
Various resources, such as books, websites and articles, for improving your Erlang development skills and knowledge.

## Websites
*Useful web and Erlang-related websites and newsletters.*

* [Erlang Central](https://erlangcentral.org/) - An awesome collections of erlang resource along with live community chat for discussing and seeking help.

## Books
*Fantastic books and e-books.*

* [Learn You Some Erlang](http://learnyousomeerlang.com/) - Learn you some Erlang - for great good! A very thorough resource covering everything from beginning Erlang programming to large-scale development and deployment.

## Web Reading
*General web-development-related reading materials.*

## Erlang Reading
*Erlang-releated reading materials.*

## Screencasts
*Cool video tutorials.*

# Contributing
Please see [CONTRIBUTING](https://github.com/drobakowski/awesome-erlang/blob/master/CONTRIBUTING.md) for details.
