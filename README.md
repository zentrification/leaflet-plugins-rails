# leaflet-plugins-rails

[leaflet-plugins](https://github.com/shramov/leaflet-plugins) packaged for the rails asset pipeline

## Installation

Add `leaflet-plugins-rails` to your Gemfile and run `bundle install`:

    gem 'leaflet-plugins-rails'

Include javascript assets in `app/assets/javascripts/application.js`

        //= require leaflet-plugins

You can fine tune the javascript assets to suit your needs

        //= require leaflet-plugins/control
        //= require leaflet-plugins/layer/tile
        //= require leaflet-plugins/layer/vector

Include stylesheet assets in `app/assets/stylesheets/application.css`

        *= require distance
        *= require osb

## Contributing

Fork & send a pull with decent commit messages

## Credits

[Pavel Shramov](https://github.com/shramov)
