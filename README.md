# docker-ruby-nodejs

[![Circle CI](https://circleci.com/gh/shawnzhu/docker-ruby-nodejs.svg?style=shield)](https://circleci.com/gh/shawnzhu/docker-ruby-nodejs)

Dockerfile that generates an image for people who use [Node.js](http://nodejs.org/) and [Ruby](https://www.ruby-lang.org/) on ubuntu.

## Build image

    $ docker build -t=ruby-nodejs:0.12.7

## What's included

* Ubuntu 12.04
* ruby 2.1.1
* [Ruby bundler](https://github.com/bundler/bundler/)
* Node.js - Thanks to [dockerfile/nodejs](https://github.com/dockerfile/nodejs)

## Pull image

    $ docker pull shawnzhu/ruby-nodejs:0.12.7

## Testing

Ruby 2.0+, bundler and docker required.

    $ bundle
    $ bundle exec rspec
