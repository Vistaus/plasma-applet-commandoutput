## v10 - April 30 2020

* Add fixed height setting (Issue #18)
* Always use a fixed size font (Issue #18)
* Wrap only if we don't have a fixed width (not horz panel).
* Show truncated/elided text in tooltip.

## v9 - November 15 2019

* Change hardcoded min interval to 0ms instead of 1000ms.
* Only remove final newline in stdout. Previous behavior can be re-enabled in the config. (Issue #3)
* Add ability to set default text+outline color like simpleweather.
* Run command immediately on command change. Fixes bug where widget stops updating if command was changed after command was run, but before the command finishes.
* Add ability to set a fixed width (off by default).
* Update Dutch translation by @Vistaus (Pull Request #16)

## v8 - February 20 2019

* Fix click + mousewheel commands no longer serializing (Issue #6)

## v7 - February 13 2019

* Added Dutch translation by @Vistaus (Pull Request #10)
* Added support opening html links `<a href="">Link</a>` in your web browser.

## v6 - February 9 2019

* Fix boldness not persisting.
* Add ability to center/right align output, italicize and underline.
* Add ability to hide background when used as a desktop widget.
* Fix selecting the default font after changing to another font.
* Add ability to run a command on click / mousewheel (Issue #6)

## v5 - May 6 2018

* Support use as a Desktop Widget.
* Add ability to change the font family, size, and boldness.

## v4 - March 12 2018

* Run command on load so in case the interval is very long.

## v3 - April 5 2017

* Use a lower version of QtQuick.Layouts so that the widget works with Plasma 5.5 (Ubuntu 16.04)

## v2 - February 20 2017

* Fix configuring intervals other than 1 second. Thanks @sheerhub
* Use the utilities-terminal icon

## v1 - December 26 2016

* First release
