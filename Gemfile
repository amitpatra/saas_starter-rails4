source 'https://rubygems.org'
ruby '2.0.0'
#ruby-gemset=saas_starter

# Default Rails gems
gem 'rails', '4.0.2'
gem 'sass-rails', '~> 4.0.1' # Use SCSS for stylesheets
gem 'uglifier', '>= 2.1.1' # Use Uglifier as compressor for JavaScript assets
gem 'coffee-rails', '~> 4.0.1' # Use CoffeeScript for .js.coffee assets and views
gem 'jquery-rails', '3.0.4' # Use jquery as the JavaScript library
gem 'turbolinks' # Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'jbuilder', '~> 1.2' # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder

group :production do
  gem "pg", "~> 0.17.0" # Database for Heroku
  gem 'rails_12factor', '0.0.2' # Heroku support
  gem 'thin' # Web server for Heroku, need to look at Unicorn also
end

group :development, :test do
  gem 'sqlite3', '1.3.8'
  gem 'quiet_assets' # Turn off assets log
  gem 'rspec-rails', '2.14.1' # Testing framework for Rails
end

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end
