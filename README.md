# \<paper-checkbox-group\>

A checkbox group in the style of polymer paper check box. Pass an array as 'items' attribute to build the group and strore the value in atribute 'value'.

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
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

### Done
Add array as parameter.
Return value in attribute.
Make input array configurable.

### To Do
Tests
Error messsage on empty selection.
Only allow to select a single checkbox.
Disable specific checkboxes.
