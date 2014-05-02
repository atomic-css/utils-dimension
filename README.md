# Atomic utilities: dimension

Utilities for dimension-related CSS.
See [other utilities](https://github.com/atomic-css/utils).

Read more about [Atomic framework](https://github.com/atomic-css/atomic).

## Installation

* [__Bower:__](http://bower.io)
  `bower install --save atomic-css-utils-dimension`
* [__Component(1):__](http://component.io)
  `component install atomic-css/utils-dimension`
* __Download:__
  [zip](https://github.com/atomic-css/utils-dimension/zipball/master),
  [tar.gz](https://github.com/atomic-css/utils-dimension/tarball/master)
* __Git:__ `git clone https://github.com/atomic-css/utils-dimension.git`

## Available classes

* `u-sizeAuto` - make an element its calculated width
* `u-size1of1` - 100% width
* `u-sizeXofY` (numerous) - specify the proportional width of an object
* `u-flexOne` - grow by a factor of 1, regardless of intrinsic width
* `u-flexAuto` - grow and shrink by a factor of 1, regardless of intrinsic width
* `u-flexNone` - disable flexible size

`X` must be an integer less than `Y`.

`Y` can be any of the following numbers: 2, 3, 4, 5, 6, 8, 10, 12

## Browser support

* Google Chrome (latest)
* Opera (latest)
* Firefox 4+
* Safari 5+
* Internet Explorer 8+ (10+ for flex sizes)