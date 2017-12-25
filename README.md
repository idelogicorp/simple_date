# SimpleDate

Welcome to our new gem! In this directory, you'll find the files you need to be able to package up your Ruby library into a gem. Put your Ruby code in the file `lib/simple_date`. To experiment with that code, run `bin/console` for an interactive prompt.


## Installation

Add this line to your application's Gemfile:

```ruby
gem 'simple_date'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install simple_date

## Usage
Import :
```ruby
require 'simple_date'
```
And then use :
```ruby
# time = Time.strftime("%Y-%m-%d %H:%M:%S")
=> "2017-12-25 15:00:42"

 
def self.get_month(time)
  return SimleDate.month(time)
end
```
result : Desember


## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at [https://github.com/idelogicorp/simple_date](https://github.com/idelogicorp/simple_date). This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the SimpleDate project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/idelogicorp/simple_date/CODE_OF_CONDUCT.md).
