# Flatui

A Simple gem for bootstrap based flat-ui (http://designmodo.com/flat-free/) to be made available in asset pipeline

## Installation

Add this line to your application's Gemfile:

    gem 'flatui'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install flatui

## Usage

After bundling the gem in your rails app, add your flat-ui css to your application.css and delete scaffold.scss if any.
  
    *= requrie bootstrap
    *= require flat-ui

and the following js to your application.js

    //= require flat-ui-app
    //= require bootstrap-tooltip
    //= require custom_radio     
    //= require html5shiv
    //= require jquery.dropkick-1.0.0  
    //= require jquery.tagsinput   
    //= require custom_checkbox_and_radio  
    //= require icon-font-ie7  
    //= require jquery.placeholder
    //= require lte-ie7-24

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## To-do

1. Add fonts 
2. Add generator for setting up css and js in the respective paths
3. Add generator for views

## License 

MIT See License file


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/saurabhbhatia/flatui/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

