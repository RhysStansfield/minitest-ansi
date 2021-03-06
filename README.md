# MiniTest::ANSI

[![Gem Version][badge-fury-badge]][badge-fury-site]
[![Build Status][travis-badge]][travis-site]
[![Dependency Status][gemnasium-badge]][gemnasium-site]
[![Code Climate][cc-badge]][cc-site]
[![Coverage Status][coveralls-badge]][coveralls-site]

Colorize your minitest output using ANSI colors.

Tested under MRI 1.8, 1.9 and 2.0, JRuby and Rubinius.

## Versioning

Minitest-ansi 0.1.x series should work with minitest up to 4.x.  
Minitest-ansi 0.2.x is expected to work with minitest 5.x.

## How it looks

![Screenshot][screenshot]

## Installation

Add this line to your application's Gemfile:

```ruby
group :test do
  gem 'minitest-ansi'
end
```

And then execute:

```bash
$ bundle
```

Or install it yourself:

```bash
$ gem install minitest-ansi
```

## Usage

You probably want to add this to your `test_helper.rb` (or equivalent).

```ruby
require 'minitest/ansi'

MiniTest::ANSI.use!
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

[badge-fury-badge]: https://badge.fury.io/rb/minitest-ansi.png
[badge-fury-site]: http://badge.fury.io/rb/minitest-ansi
[cc-badge]: https://codeclimate.com/github/rizzatti/minitest-ansi.png
[cc-site]: https://codeclimate.com/github/rizzatti/minitest-ansi
[coveralls-badge]: https://coveralls.io/repos/rizzatti/minitest-ansi/badge.png?branch=master
[coveralls-site]: https://coveralls.io/r/rizzatti/minitest-ansi
[gemnasium-badge]: https://gemnasium.com/rizzatti/minitest-ansi.png
[gemnasium-site]: https://gemnasium.com/rizzatti/minitest-ansi
[screenshot]: https://github.com/rizzatti/minitest-ansi/raw/master/images/screenshot.png
[travis-badge]: https://travis-ci.org/rizzatti/minitest-ansi.png
[travis-site]: https://travis-ci.org/rizzatti/minitest-ansi
