# SpookyJS for CSS Testing

Drive [CasperJS](http://casperjs.org/) from Node.js.

For full details on using SpookyJS, refer to the [SpookyJS README](https://github.com/WaterfallEngineering/SpookyJS/README.md)

This README will cover using SpookyJS for CSS testing using the [GhostStory](https://github.com/thingsinjars/GhostStory/) set of CSS [Cucumber.js](https://github.com/cucumber/cucumber-js/) steps. It also makes use of [PhantomCSS](https://github.com/Huddle/PhantomCSS) for some of the steps.

## Installation

### Prerequisites

* [Node.js](http://nodejs.org)
* [PhantomJS](http://phantomjs.org/) *note:* version 1.6 or 1.7. Currently not working with 1.8
* [CasperJS](http://casperjs.org/)

### Submodules
Once these prerequisites are installed, the easiest way to ensure all the submodules are initialised and installed is:

    git clone --recursive git://github.com/thingsinjars/SpookyJS.git
    
This will pull in GhostStory and a slightly modified version of PhantomCSS.


## Make target

An example test suite is included in `GhostStory/css.feature` and can be run from the command-line using:
 
``` shell
$ make ghost
```

## CSS steps

The GhostStory README contains details of the steps available for Cucumber feature files.