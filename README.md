x-publish
========

This module has just a little utility script for all x-component modules

it generates the README.md

and maintains a component.json

Usage
-----
use x-publish as a devDependency in the package.json
and call the script prepublish.sh:

    "devDependencies": {
      "x-common": "~0.0"
    },
    ....

    "scripts": {
       "prepublish": "./node_modules/x-common/scripts/prepublish.sh <list your source files>"
    },
