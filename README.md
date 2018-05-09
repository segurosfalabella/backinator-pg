# Backinator::Pg

This gem provide a set of tasks to backup a remote postgres database. It store temporaly in a given file system path and then push the 
backup file to a remote storage like Azure Storage, AWS S3, etc. To experiment with code, run `bin/console` for an interactive prompt.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'backinator-pg'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install backinator-pg

## Usage
```bash
bundle exec rake backinator_pg:run
```
TODO: We are working on:

- [] Config generators
- [] Tests
- [] Some beers

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/backinator-pg. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the Backinator::Pg project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/[USERNAME]/backinator-pg/blob/master/CODE_OF_CONDUCT.md).

# AUTHOR
Everyone is welcome to join us! Happy coding!
* Sandro Gómez Araya [@mrsangrin](https://github.com/mrsangrin).
