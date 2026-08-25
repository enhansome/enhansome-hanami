# Awesome Hanami with stars

A collection of awesome ruby gems and projects for hanami development.

The goal is to help every hanami developer to build an awesome product/service.

* [Hanami Gem List](#hanami-gem-list)
  * [Assets](#assets)
  * [Authentication and OAuth](#authentication-and-oauth)
  * [File Uploading](#file-uploading)
  * [Performance Monitoring](#performance-monitoring)
  * [Testing](#testing)
  * [Database](#database)
  * [Pagination](#pagination)
  * [CLI](#cli)
  * [Building APIs](#building-apis)
  * [API Documentation](#api-documentation)
  * [Deploy](#deploy)
  * [Editors and IDE](#editors-and-ide)
* [Vanilla Libraries and Hanami](#vanilla-libraries-and-hanami)
* [Hanami Project List](#hanami-project-list)
* [Useful Links](#useful-links)
  * [Blog Posts](#blog-posts)
  * [Benchmarks](#benchmarks)
  * [User Groups](#user-groups)

## Hanami Gem List

### Assets

* [vite\_hanami](https://github.com/ElMassimo/vite_ruby/tree/main/vite_hanami) ⭐ 1,592 | 🐛 49 | 🌐 Ruby | 📅 2026-07-03 - A RubyGem to allow you to use the Vite.js as your asset pipeline in Hanami.
* [hanami-webpack](https://github.com/samuelsimoes/hanami-webpack) ⚠️ Archived - A RubyGem to allow you to use the Webpack as your asset pipeline in Hanami.
* [hanami-bootstrap](https://github.com/davydovanton/hanami-bootstrap) ⭐ 14 | 🐛 5 | 🌐 Ruby | 📅 2022-09-19 - Bootstrap wrapper for hanami framework.
* [jquery-hanami](https://rubygems.org/gems/jquery-hanami) - This gem provides jQuery and the jQuery-ujs driver for your Hanami application.

### Authentication and OAuth

* [tachiban](https://github.com/sebastjan-hribar/tachiban) ⭐ 35 | 🐛 0 | 🌐 Ruby | 📅 2026-03-06 - Authentication with bcrypt for Hanami apps
* [hanami-fumikiri](https://github.com/theCrab/hanami-fumikiri) ⭐ 26 | 🐛 2 | 🌐 Ruby | 📅 2016-08-21 - JWT authentication wrapper for hanami apps
* [omniauth-hanami](https://github.com/katafrakt/omniauth-hanami) ⭐ 14 | 🐛 0 | 🌐 Ruby | 📅 2018-06-20 – Allows to use Hanami repository as OAuth provider (similar to [omniauth-identity](https://github.com/intridea/omniauth-identity) ⭐ 363 | 🐛 7 | 🌐 Ruby | 📅 2026-08-11)
* [hanami-id](https://github.com/leemour/hanami_id) ⭐ 14 | 🐛 26 | 🌐 Ruby | 📅 2022-03-30 - Large authentication library, with generators
* [hanami-rodauth](https://github.com/davydovanton/hanami-rodauth) ⭐ 7 | 🐛 0 | 🌐 Ruby | 📅 2019-08-28 - Rodauth wrapper for hanami apps

### Authorization

* [kan](https://github.com/davydovanton/kan) ⭐ 235 | 🐛 13 | 🌐 Ruby | 📅 2020-03-12 - Simple, light and functional authorization library
* [tachiban](https://github.com/sebastjan-hribar/tachiban) ⭐ 35 | 🐛 0 | 🌐 Ruby | 📅 2026-03-06 - Tachiban includes policy based authorization support
* [jay\_doubleu\_tee](https://github.com/hanamimastery/jay_doubleu_tee) ⭐ 17 | 🐛 1 | 🌐 Ruby | 📅 2023-01-16 - JWT authorization wrapper for all Ruby apps, including Hanami projects.

### File Uploading

* [hanami-shrine](https://github.com/katafrakt/hanami-shrine) ⭐ 27 | 🐛 2 | 🌐 Ruby | 📅 2021-04-13 - Upload solution for Hanami using Shrine library

### Performance Monitoring

* [newrelic-hanami](https://github.com/artemeff/newrelic-hanami) ⭐ 12 | 🐛 1 | 🌐 Ruby | 📅 2019-06-17 - Gem for connecting NewRelic and Hanami

### Testing

* [rspec-hanami](https://github.com/davydovanton/rspec-hanami) ⭐ 45 | 🐛 7 | 🌐 Ruby | 📅 2020-10-10 - RSpec Matchers for Hanami
* [hanami-fabrication](https://github.com/jodosha/hanami-fabrication) ⭐ 16 | 🐛 1 | 🌐 Ruby | 📅 2022-08-11 - Utility to easily integrate [Fabrication](https://www.fabricationgem.org/) gem and Hanami
* [shoulda-hanami](https://github.com/mcorp/shoulda-hanami) ⚠️ Archived - Making tests easy on the fingers and eyes, but on hanami (old shoulda-lotus)

### Database

* [rom\_sql\_graph](https://github.com/davydovanton/rom_sql_graph) ⭐ 9 | 🐛 1 | 🌐 Ruby | 📅 2020-05-06 - DB (sql) association graph for hanami and rom projects
* [hanami-rethinkdb](https://github.com/angeloashmore/hanami-rethinkdb) ⭐ 6 | 🐛 1 | 🌐 Ruby | 📅 2016-05-13 - RethinkDB adapter for Hanami::Model
* [hanami-sequel](https://github.com/malin-as/hanami-sequel) ⭐ 4 | 🐛 2 | 🌐 Ruby | 📅 2023-03-16 - A Sequel-only replacement of [hanami-model](https://github.com/hanami/model) ⚠️ Archived, including CLI extension and model generation.

### Pagination

* [pagy](https://github.com/ddnexus/pagy) ⭐ 4,989 | 🐛 0 | 🌐 Ruby | 📅 2026-08-24 - The ultimate pagination ruby gem. [Integration to hanami](http://katafrakt.me/2018/06/01/integrating-pagy-with-hanami/).
* [hanami-pagination](https://github.com/davydovanton/hanami-pagination) ⭐ 14 | 🐛 4 | 🌐 Ruby | 📅 2018-06-08 - Pagination gem for your hanami applications. Based on ROM::Pagination plugin.

### Events

* [hanami-events-cloud\_pubsub](https://github.com/adHawk/hanami-events-cloud_pubsub) - A hanami-events adapter for Google Cloud Pub/Sub.

### CLI

* [hanami-scaffold](https://github.com/davydovanton/hanami-scaffold) ⭐ 13 | 🐛 3 | 🌐 Ruby | 📅 2017-08-21 - Make hanami scaffolds faster.
* [hanami-zsh](https://github.com/davydovanton/hanami-zsh) ⭐ 7 | 🐛 1 | 📅 2017-08-18 - Zsh plugin for hanami projects.

### Building APIs

* [hanami-serializer](https://github.com/davydovanton/hanami-serializer) ⭐ 21 | 🐛 6 | 🌐 Ruby | 📅 2019-06-11 - Serializer library for hanami applications
* [hanami-jbuilder](https://github.com/vladfaust/hanami-jbuilder) ⭐ 4 | 🐛 0 | 🌐 Ruby | 📅 2016-04-18 - Support for rendering JBuilder templates for Hanami apps
* [jsonapi-hanami](http://jsonapi-rb.org) - Efficiently and conveniently build [JSON API](http://jsonapi.org)-compliant APIs with Hanami.

### API Documentation

* [had](https://github.com/nsheremet/had) ⭐ 7 | 🐛 1 | 🌐 Ruby | 📅 2018-04-16 - Hanami API Documentation

### Deploy

* [mina-hanami](https://github.com/mgrachev/mina-hanami) ⚠️ Archived - [Mina](https://github.com/mina-deploy/mina) ⭐ 4,356 | 🐛 35 | 🌐 Ruby | 📅 2024-08-01 plugin for Hanami.
* [hanami-docker](https://github.com/gruz0/hanami-docker) ⭐ 13 | 🐛 0 | 🌐 Makefile | 📅 2018-08-12 - Dockerize your Hanami application
* [capistrano-hanami](https://github.com/mgrachev/capistrano-hanami) ⚠️ Archived - Hanami tasks for [Capistrano](https://github.com/capistrano/capistrano) ⭐ 12,984 | 🐛 65 | 🌐 Ruby | 📅 2026-07-19.
* [mina-proteus](https://github.com/apontini/mina-proteus) ⭐ 0 | 🐛 0 | 🌐 Ruby | 📅 2019-06-13 - [Mina](https://github.com/mina-deploy/mina) ⭐ 4,356 | 🐛 35 | 🌐 Ruby | 📅 2024-08-01 plugin for Hanami than allows you to deploy a specific application in a specific environment.

### Editors and IDE

* [Vim Hanami](https://github.com/sovetnik/vim-hanami) ⭐ 12 | 🐛 0 | 🌐 Vim script | 📅 2019-01-22 - plugin that gives you faster navigation between semantically associated files, like Action <-> View, Entity <-> Repository or Spec <-> Entity.
* [projectile-hanami](https://github.com/avdgaag/projectile-hanami) ⚠️ Archived - Projectile Hanami is an Emacs minor mode, based on Projectile, for navigating Hanami projects.
* [Vim Minispec](https://github.com/sovetnik/vim-minispec) ⭐ 2 | 🐛 0 | 🌐 Vim script | 📅 2020-08-14 - plugin runs your Gem or Hanami Minitest specs and displays the results in Vim quickfix.
* [How to run Hanami in RubyMine](https://medium.com/@tetyanachupryna/how-to-run-hanami-in-rubymine-dff342cb0114#.7jb2bjq9f)

## Vanilla Libraries and Hanami

* [Factory Bot](https://github.com/thoughtbot/factory_bot) ⭐ 8,170 | 🐛 78 | 🌐 Ruby | 📅 2026-08-21 - [Hanami with Factory Bot](https://gist.github.com/rafaels88/8437edababcf38ee193b2ba0265e78b9)
* [omniauth](https://github.com/intridea/omniauth) ⭐ 8,101 | 🐛 105 | 🌐 Ruby | 📅 2026-02-27 - [Hanami with OAuth](http://codetunes.com/2016/hanami-with-oauth/)
* [mongoid](https://github.com/mongodb/mongoid) ⭐ 3,913 | 🐛 277 | 🌐 Ruby | 📅 2026-08-21 - [github](https://github.com/michalvalasek/hanami-mongoid) ⭐ 2 | 🐛 0 | 🌐 Ruby | 📅 2016-05-23
* [letter\_opener](https://github.com/ryanb/letter_opener) ⭐ 3,840 | 🐛 2 | 🌐 Ruby | 📅 2026-04-25 - [Preview hanami emails in browser](http://blog.davydovanton.com/2016/05/21/preview-hanami-emails-in-browser/)
* [Trailblazer](https://github.com/apotonick/trailblazer) ⭐ 3,477 | 🐛 38 | 🌐 Ruby | 📅 2025-07-15 - [Hanami with Trailblazer](https://github.com/apotonick/gemgem-hanami) ⭐ 14 | 🐛 0 | 🌐 Ruby | 📅 2016-07-13
* [I18n](https://github.com/svenfuchs/i18n) ⭐ 1,031 | 🐛 61 | 🌐 Ruby | 📅 2026-06-19 - [From Rails to Hanami Part 3](http://rpanachi.com/2016/04/25/from-rails-to-hanami-part3-sidekiq-workers-i18n-timezone-issues-core-ext)
* [Sidekiq](http://sidekiq.org) - [From Rails to Hanami Part 3](http://rpanachi.com/2016/04/25/from-rails-to-hanami-part3-sidekiq-workers-i18n-timezone-issues-core-ext), [Use Sidekiq With Hanami](http://www.strauss.io/blog/2016-use-sidekiq-with-hanami.html)
* [Sequel plugins](http://sequel.jeremyevans.net/plugins.html) - [From Rails to Hanami Part 3](http://rpanachi.com/2016/04/25/from-rails-to-hanami-part3-sidekiq-workers-i18n-timezone-issues-core-ext)

## Hanami Project List

### Closed Source

* [loan application platform](http://creditas.com.br) - A Brazilian startup for credit loan using a car or house as a guarantee.

### Open Source

* [OSSBoard](http://www.ossboard.org) - Simple way to connect developers and oss maintainers ([Sources](https://github.com/davydovanton/ossboard) ⭐ 99 | 🐛 24 | 🌐 Ruby | 📅 2019-03-16).
* [pinfluence](https://github.com/prosi-org/pinfluence) ⭐ 27 | 🐛 3 | 🌐 Ruby | 📅 2018-08-25 - All world influencers in a map
* [contributors.hanamirb.org](http://contributors.hanamirb.org) - All hanami contributors in one place ([Sources](https://github.com/hanami/contributors) ⚠️ Archived).
  <http://github.com/makedecision-org/core> ⭐ 6 | 🐛 6 | 🌐 Ruby | 📅 2019-02-07
* [cookie\_box](https://github.com/davydovanton/cookie_box) ⭐ 13 | 🐛 17 | 🌐 Ruby | 📅 2018-09-21 - Follow and control issues from several repositories from one place.
* [makedecision](http://github.com/makedecision-org/core) ⭐ 6 | 🐛 6 | 🌐 Ruby | 📅 2019-02-07 - Make decision faster.
* [Flashcard Genius](http://flashcard-genius.com) - Create, print and learn flashcards ([Sources](https://github.com/Bajena/flashcard-genius) ⭐ 5 | 🐛 19 | 🌐 Ruby | 📅 2023-04-12)
* [app.dartboard.io](http://app.dartboard.io) - Online darts scorer app built with Hanami([Sources](https://github.com/stravid/datsu-api))
* [scripta.io](http://www.scripta.io/home) - A platform for creating and sharing documents on the web ([Sources](https://github.com/jxxcarlson/noteshare)).

### Play/Pet projects

* [hanami-jwt-example](https://github.com/nickgnd/hanami-jwt-example) ⭐ 31 | 🐛 4 | 🌐 Ruby | 📅 2018-10-17 - A simple JSON API web application built with Hanami which provides jwt-authentication, password encryption and CORS support.
* [hanami-realworld-example-app](https://github.com/blrB/hanami-realworld-example-app) ⭐ 16 | 🐛 0 | 🌐 Ruby | 📅 2022-12-19 - Hanami codebase containing real world examples (CRUD, auth, tests etc) that adheres to the [RealWorld](https://github.com/gothinkster/realworld) ⭐ 84,139 | 🐛 32 | 🌐 TypeScript | 📅 2026-08-13 spec and API.
* [bookshelf-delivery-example](https://github.com/bruz/bookshelf-delivery-example) ⭐ 14 | 🐛 1 | 🌐 Ruby | 📅 2017-04-11 - An example app with a web GUI, API and CLI using shared interactors.
* [upment-hanami](https://github.com/AlexanderMint/upment-hanami) ⚠️ Archived - App on Hanami: JWT, GraphQL, RSpec and [REACT client](https://github.com/AlexanderMint/upment-client) ⚠️ Archived
* [hanami-chat-example](https://github.com/nickgnd/hanami-chat-example) ⭐ 9 | 🐛 4 | 🌐 Ruby | 📅 2023-01-18 - A basic chat application built with Hanami and [LiteCable](https://github.com/palkan/litecable) ⭐ 303 | 🐛 0 | 🌐 Ruby | 📅 2026-07-25 (compatible with [AnyCable](http://anycable.io/))
* [Burn My Fat!](https://github.com/burn-my-fat/web) ⚠️ Archived (ru) – Backend for a mobile application that will help you make your body more beautiful. [YouTube](https://www.youtube.com/channel/UCDAXAwUlu-lIbjRXCUtc6oA)
* [distruct-me](https://github.com/MorozovaLiuda/distruct-me) ⭐ 2 | 🐛 0 | 🌐 Ruby | 📅 2016-10-16 - App on Hanami for self-distructing messages
* [Deutsch](https://github.com/mjacobus/deutsch) ⭐ 1 | 🐛 23 | 🌐 Ruby | 📅 2022-12-06 - prototype tool for learning German.
* [repressed\_museum](https://github.com/vasspilka/repressed_museum) ⚠️ Archived - A simple mostly static website, features basic i18n and docker integration

## Useful Links

* [Community page on the official site](http://hanamirb.org/community/)
* [Hanami Mastery](https://hanamimastery.com) - Articles and Video tutorials, featuring Hanami, its dependencies (ROM-RB, DRY-RB) and all great ruby projects that may be integrated with Hanami.

### Blog Posts

* [What I learned building an app in Hanami](https://rossta.net/blog/what-i-learned-about-hanami.html)
* [Livereload and Hanami](https://defman.me/blog/hanami-love-livereload/)
* [Deploying Hanami web application with Puma, Nginx and PostgreSQL using Docker](https://sebastjan-hribar.github.io/programming/2018/07/19/hanami-app-deployment-example.html)
* [Getting Started with Hanami and GraphQL](https://blog.simplificator.com/2016/12/07/getting-started-with-hanami-and-graphql/)
* [IoT Saga - My first (for development) setup for a Hanami application](http://gabrielmalakias.com.br/hanami/iot/docker/2017/02/14/iot-saga-my-setup-for-a-hanami-application.html)
* [Websockets! Connecting LiteCable to Hanami](http://gabrielmalakias.com.br/ruby/hanami/iot/2017/05/26/websockets-connecting-litecable-to-hanami.html)

### User Groups

* [São Paulo, Brasil](https://twitter.com/hanamirb_sp) - Grupo de usuários Hanami-rb de São Paulo.
* [Facebook, Brasil](https://www.facebook.com/groups/1415625271796799) - Grupo brasileiro de discussão no Facebook.
* [Russian telegram community](https://t.me/hanamirb_ru).

### Benchmarks

* [hanami-bench](https://github.com/davydovanton/hanami-bench) ⭐ 6 | 🐛 0 | 🌐 Ruby | 📅 2017-10-10 - Benchmarks for hanami

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-25._
