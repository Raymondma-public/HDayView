Tachyon [![Build Status](https://travis-ci.com/linkedin/Tachyon.svg?branch=master)](https://travis-ci.com/linkedin/Tachyon)
========

An Android library that provides a customizable Horizontalcalendar day view.


Overview
--------

Tachyon is designed to provide a familiar visualization of a calendar day. The rendering is done by the `DayView` class, which takes a list of events and displays them using a custom layout algorithm.

Usage
-----

To use Tachyon, you can either directly reference the `DayView` class in your layout files/code, or you can subclass `DayView` to customize the experience.

Sample App
----------

The ''tachyon-sample'' app contains an example of using the library.

Testing
-------

We use Mockito for our unit tests. You can run them via the `clean test` Gradle tasks.
