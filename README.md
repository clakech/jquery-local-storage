# jQuery Local Storage Plugin

Version 0.1.0

## Overview

This is an implementation of HTML5 localStorage with cookie fallback for older browsers.

Uses a built-in implementation of the excellent [jquery-cookie](https://github.com/carhartl/jquery-cookie) plugin,
 and [JSON-js](https://github.com/douglascrockford/JSON-js] for adding the native JSON.parse) and JSON.stringify()
functions in older browsers.

## Usage

All values are automatically stringified/parsed, so use arrays, objects, strings, etc.

To retrieve values, use

    $.localStorage(key)

To set values, use

    $.localStorage(key, value)

