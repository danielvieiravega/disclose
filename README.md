# Disclose

Pack your Node.js project into an executable without recompiling Node.js.

[![Gem Version](https://badge.fury.io/rb/disclose.svg)](https://badge.fury.io/rb/disclose)
[![Build Status](https://travis-ci.org/pmq20/disclose.svg)](https://travis-ci.org/pmq20/disclose)
[![Code Climate](https://codeclimate.com/github/pmq20/disclose/badges/gpa.svg)](https://codeclimate.com/github/pmq20/disclose)
[![codecov.io](https://codecov.io/github/pmq20/disclose/coverage.svg?branch=master)](https://codecov.io/github/pmq20/disclose?branch=master)
[![](http://inch-ci.org/github/pmq20/disclose.svg?branch=master)](http://inch-ci.org/github/pmq20/disclose?branch=master)

## Installation

    $ gem install disclose

## Dependencies

Make sure that your system has the following components,

- tar
- xxd
- cc or cl.exe

## Usage

    $ disclose [node_path] [project_path]

## Example

On Windows,

    > disclose "C:\Program Files\nodejs\node.exe" "Z:\node_modules\coffee-script"

On Unix,

    $ disclose /usr/local/bin/node /usr/local/lib/node_modules/coffee-script

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
