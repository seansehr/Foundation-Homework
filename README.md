Foundation-Homework
===================

## Steps to get Zurb Foundation 5 to work with Rails 4

1. Install Zurb Foundation Rails gem
 1. `gem install foundation-rails`
2. add `gem 'foundation-rails'` to your Gemfile
 1. need to have `sass-rails`
3. bundle
4. rails g foundation:install
 1. This will generate a foundation_and_overrides.scss in `app/assets/stylesheets` for any overrides
 2. This will add `$(function(){ $(document).foundation(); });` to the application.js to trigger Foundation's javascript functions

Enjoy