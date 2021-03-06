# [Foundation](http://foundation.zurb.com)

[![Build Status](https://travis-ci.org/debianw/foundation.png?branch=master)](https://travis-ci.org/debianw/foundation)

Foundation is the most advanced responsive front-end framework in the world. You can quickly prototype and build sites or apps that work on any kind of device with Foundation, which includes layout constructs (like a fully responsive grid), elements and best practices.

To get started, check out <http://foundation.zurb.com/docs>

## Installation

  Install with [component(1)](http://component.io):

    $ component install debianw/component-foundation

## Quickstart

To get going with Foundation you can:

  * [Download the latest release](http://foundation5.zurb.com/cdn/releases/foundation-latest.zip)
  * [Install with Bower](http://bower.io): `bower install zurb/bower-foundation`

## What's included?

```
foundation/
├── css/
│   ├── foundation.css
│   ├── foundation.min.css
├── js/
│   ├── foundation.js
│   └── foundation.min.js
└── scss/
    ├── foundation.scss
    └── foundation/
```

## Documentation

Foundation uses [Assemble.io](http://assemble.io) and [Grunt](http://gruntjs.com/) to generate it's [documentation pages](http://foundation.zurb.com/docs). Documentation can also be run from your local computer:

### View documentation locally

You'll want to clone the Foundation repo first and install all the dependencies. You can do this using the following commands:

```
git clone git@github.com:zurb/foundation.git
cd foundation
npm install -g grunt-cli
npm install
```

Then just run `grunt` and the documentation will be compiled:

```
foundation/
├── dist/
│   └── ...
├────── docs/
│       └── ...
```

Copyright (c) 2013 ZURB, inc.
