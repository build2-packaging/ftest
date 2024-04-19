# ftest - A simple and limited unit-test framework for C++ 98 

This is a `build2` package for the
[`ftest`](https://github.com/nemtrif/ftest) C++ testing framework.
You may want to use FTest if you want to quickly set-up a testing framework with
an easy path to migrating to GoogleTest once you need more features.

Another use-case scenario for FTest is when you need to compile your code
(including the tests) with C++ 98.

Or, you may just like the simplicity and small size of FTest and do not need the
features offered by bigger testing frameworks.


## Usage

To start using `ftest` in your project, add the following `depends`
value to your `manifest`, adjusting the version constraint as appropriate:

```
depends: ftest ^0.3.0
```

Then import the library in your `buildfile`:

```
import libs = ftest%lib{ftest}
```
