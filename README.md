# \<coastal-cleanup-day\>

![coastal-cleanup-day](https://github.com/CoastalCommission/Coastal-Cleanup-Day/blob/master/images/screenshot-1.png?raw=true)

![coastal-cleanup-day](https://github.com/CoastalCommission/Coastal-Cleanup-Day/blob/master/images/screenshot-2.png?raw=true)


## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed.
Then run `bower install`
and `polymer serve --open` to serve your application locally.

## Viewing Your Application

```
$ polymer serve --open
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
