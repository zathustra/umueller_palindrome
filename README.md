# Palindrome detector

`umueller_palindrome` is a sample Ruby gem created in [*Learn Enough Ruby to Be Dangerous*](https://www.learnenough.com/ruby-tutorial) by Michael Hartl.

## Installation

To install `umueller_palindrome`, add this line to your application's Gemfile:

```ruby
gem 'umueller_palindrome'
```

And then install as follwos:

    $ bundle install

Or install it yourself as:

    $ gem install umueller_palindrome

`umueller_palindrome` adds a `palindrome?` method to the `String` class, and can be used as follows:

```
$ irb
>> require 'umueller_palindrome'
>> "honey badger".palindrome?
=> false
>> "deified".palindrome?
=> true
>> "Able was I, ere I saw Elba.".palindrome?
=> true
>> phrase = "Madam, I'm Adam."
>> phrase.palindrome?
=> true
```
## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).