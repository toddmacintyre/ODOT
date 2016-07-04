source 'https://rubygems.org'

gem 'rails', '4.0.1'
gem 'sqlite3'
gem 'sass-rails', '~> 4.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

group :development, :test do
	gem 'rspec-rails', '~> 2.0'
end

group :test do
	gem 'capybara', '~> 2.1.0'
	gem 'shoulda-matchers', '~> 2.4.0'
end

# message after using bundler for odot
# IMPORTANT! Some of the defaults have changed in Capybara 2.1. If you're experiencing failures,
# please revert to the old behaviour by setting:

#     Capybara.configure do |config|
#       config.match = :one
#       config.exact_options = true
#       config.ignore_hidden_elements = true
#       config.visible_text_only = true
#     end

# If you're migrating from Capybara 1.x, try:

#     Capybara.configure do |config|
#       config.match = :prefer_exact
#       config.ignore_hidden_elements = false
#     end

# Details here: http://www.elabs.se/blog/60-introducing-capybara-2-1
