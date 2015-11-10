# PolymerIronRails

**This repository is no longer maintained.** See [polymer-elements-rails](https://github.com/alchapone/polymer-elements-rails) for an alternative.

Polymer Iron elements are a set of utility elements including general-purpose UI elements (such as icons, layout elements,
and toolbars), as well as non-UI elements providing features like AJAX, signaling and storage.

Polymer-iron-rails gem brings polymer iron web components into your Rails project.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'polymer-iron-rails', :git => "git://github.com/vsimonian/polymer-iron-rails.git"
```

And then execute:

    $ bundle

<!--- (not published to rubygems.org)
Or install it yourself as:

    $ gem install polymer-iron-rails
-->

## Getting started

In order to use Polymer iron elements you need to have
`polymer` installed in your project. Use [polymer-rails](https://github.com/alchapone/polymer-rails) gem for adding `polymer` to your Rails application.

```ruby
gem 'polymer-rails'
gem 'polymer-iron-rails', :git => "git://github.com/vsimonian/polymer-iron-rails.git"
```

After running `bundle install` require needed iron elements into your `application.html` manifest file.

    //= require polymer/polymer
    //= require iron-ajax/iron-ajax
    //= require iron-input/iron-input
    .....
    //= require iron-signals/iron-signals

Each component should be required only once. Thus if you've already required component that has dependencies, you don't need
to explicitly require any of dependencies, otherwise it will raise exception.

## Available elements

* [iron-a11y-announcer](https://elements.polymer-project.org/elements/iron-a11y-announcer)
* [iron-a11y-keys](https://elements.polymer-project.org/elements/iron-a11y-keys)
* [iron-a11y-keys-behavior](https://elements.polymer-project.org/elements/iron-a11y-keys-behavior)
* [iron-ajax](https://elements.polymer-project.org/elements/iron-ajax)
* [iron-autogrow-textarea](https://elements.polymer-project.org/elements/iron-autogrow-textarea)
* [iron-behaviors](https://elements.polymer-project.org/elements/iron-behaviors)
* [iron-collapse](https://elements.polymer-project.org/elements/iron-collapse)
* [iron-fit-behavior](https://elements.polymer-project.org/elements/iron-fit-behavior)
* [iron-flex-layout](https://elements.polymer-project.org/elements/iron-flex-layout)
* [iron-form](https://elements.polymer-project.org/elements/iron-form)
* [iron-form-element-behavior](https://elements.polymer-project.org/elements/iron-form-element-behavior)
* [iron-icon](https://elements.polymer-project.org/elements/iron-icon)
* [iron-icons](https://elements.polymer-project.org/elements/iron-icons)
* [iron-iconset](https://elements.polymer-project.org/elements/iron-iconset)
* [iron-iconset-svg](https://elements.polymer-project.org/elements/iron-iconset-svg)
* [iron-image](https://elements.polymer-project.org/elements/iron-image)
* [iron-input](https://elements.polymer-project.org/elements/iron-input)
* [iron-jsonp-library](https://elements.polymer-project.org/elements/iron-jsonp-library)
* [iron-localstorage](https://elements.polymer-project.org/elements/iron-localstorage)
* [iron-media-query](https://elements.polymer-project.org/elements/iron-media-query)
* [iron-menu-behavior](https://elements.polymer-project.org/elements/iron-menu-behavior)
* [iron-meta](https://elements.polymer-project.org/elements/iron-meta)
* [iron-overlay-behavior](https://elements.polymer-project.org/elements/iron-overlay-behavior)
* [iron-pages](https://elements.polymer-project.org/elements/iron-pages)
* [iron-range-behavior](https://elements.polymer-project.org/elements/iron-range-behavior)
* [iron-resizable-behavior](https://elements.polymer-project.org/elements/iron-resizable-behavior)
* [iron-selector](https://elements.polymer-project.org/elements/iron-selector)
* [iron-signals](https://elements.polymer-project.org/elements/iron-signals)
* [iron-validatable-behavior](https://elements.polymer-project.org/elements/iron-validatable-behavior)
* [iron-validator-behavior](https://elements.polymer-project.org/elements/iron-validator-behavior)

## Contributing

1. Fork it ( https://github.com/[my-github-username]/polymer_iron_rails/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
