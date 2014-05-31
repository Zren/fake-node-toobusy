# Fake node-toobusy

This is a [node-toobusy](https://github.com/lloyd/node-toobusy) fork. This fork is for use on dev platforms to escape having to deal with compiling C just to get things running. It always returns false when calling `toobusy()` and ruturns a lag of zero with `toobusy.lag()`.

## Installation

    npm install Zren/fake-node-toobusy
