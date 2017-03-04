Plone in React
==============

## Installation

### Prerequisites
* [Node.js==6.9.1](https://nodejs.org/)
* [Python==2.7.x](https://python.org/)
* [Git](http://git-scm.com/)

### Install dependencies

    $ yarn

### Install backend

    $ cd api
    $ python bootstrap-buildout.py
    $ ./bin/buildout

## Development

### Run backend

    $ ./bin/instance fg

### Run frontend

    $ yarn dev

### Testing

    $ yarn test
    $ yarn test:unit
    $ yarn test:e2e

If chromedriver could not be found, make sure to update with:

    ./node_modules/protractor/bin/webdriver-manager update
