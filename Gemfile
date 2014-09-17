source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.6'
gem 'bootstrap-sass', '2.0.0'
gem 'bcrypt-ruby', '3.0.1'
gem 'faker', '1.0.1'
gem 'will_paginate', '3.0.3'
gem 'bootstrap-will_paginate', '0.0.6'

# Use sqlite3 as the database for Active Record
group :development do
	gem 'sqlite3', '1.3.9'
	gem 'annotate', '~> 2.4.1.beta'
end

# Use SCSS for stylesheets
group :assets do
	gem 'sass-rails', '~> 4.0.3'
	# Use Uglifier as compressor for JavaScript assets
	gem 'uglifier', '>= 1.3.0'
	# Use CoffeeScript for .js.coffee assets and views
	gem 'coffee-rails', '~> 4.0.0'
end

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'



group :test, :development do
	gem 'rspec-rails', '2.10.0'
	gem 'guard-rspec', '0.5.5'
	gem 'guard-spork', '0.3.2'
	gem 'spork', '0.9.0'
end

group :test do
	gem 'capybara', '1.1.2'
	gem 'factory_girl_rails', '1.4.0'
	gem 'cucumber-rails', '1.2.1', require: false
	gem 'database_cleaner', '0.7.0'
end

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# adding rail_12factor to try to resolve heroku issue
gem 'rails_12factor'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
#gem 'jbuilder', '~> 2.0'

# bundle exec rake doc:rails generates the API under doc/api.
#gem 'sdoc', '~> 0.4.0',          group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin]

# Add postgresql to satisfy heroku requirements. 
# Maybe this will address the issue I had with previous 
# attempt to push to Heroku
group :production do
	gem 'pg', '0.12.2'
end

