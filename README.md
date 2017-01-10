# < bb-input-birthday >
This is an input element by written by Polymer that has a birthday value as a date format and its own validator.
___

## Polymer version
 This is written by Polymer version 1.0 .

## Installation
In your Polymer project, enter the following :
    bower install --save BBPile/bb-input-birthday

## Attributes
These attributes are belong to :
- value

  indicate a birthday that formatted by date-format.

- delimiter

  among with a year,

- limit-age
- error-essage
- show-value

The property delimiter can display the date-format like the follow example :

`example :` if delimiter="-"

     2010-10-01

## Events & Error messages
  bb-input-birthday-error-message
  error code :
  'error-year':
  'error-month' :
  'error-day' :

Specific the custom-validator made by the user.

## error-message
The multiple error-message can be displayed by each error-code originated from the validator.



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
