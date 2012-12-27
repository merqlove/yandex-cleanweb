# Yandex Cleanweb

Ruby wrapper for [Yandex Cleanweb](http://api.yandex.ru/cleanweb/) spam detector.

Work in progress...

## Installation

Add this line to your application's Gemfile:

    gem 'yandex_cleanweb'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install yandex_cleanweb

## Usage

Get the api key: [http://api.yandex.ru/cleanweb/getkey.xml](http://api.yandex.ru/cleanweb/getkey.xml)

```ruby
YandexCleanweb.api_key = "your_key"
YandexCleanweb.spam?("just phrase")
  => false
```

If you use Yandex Cleanweb in Rails app, we recommend to set up the api key in `config/initializers/yandex_cleanweb.rb`

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
