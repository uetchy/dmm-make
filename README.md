# dmm-make

Ruby binding for DMM.make

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'dmm-make'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install dmm-make

## Usage

```ruby
Dmm::Make.configure do |config|
  config.app_id = ''
end

make = Dmm::Make.new
```

## Contributing

1. Fork it ( https://github.com/uetchy/dmm-make/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
