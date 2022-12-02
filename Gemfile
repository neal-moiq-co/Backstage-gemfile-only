source 'https://rubygems.org'

ruby '2.6.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.11.1'
# Use postgresql as the database for Active Record
gem 'pg'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.3'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

# Use jquery as the JavaScript library
# gem 'jquery-rails'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
# gem 'sdoc', '~> 0.4.0',          group: :doc

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
#gem 'spring',        group: :development

gem 'airbrake', '~> 10.0.0'
gem "attr_encrypted", "~> 3.1.0"
gem 'axlsx_rails'
gem 'bitly', '1.1.2'
gem 'cancan'
gem 'chargify_api_ares', '~> 1.4.3'
gem 'classy_enum'
gem 'delayed_job_active_record'
gem 'devise'
gem 'friendly_id', '~> 5.1.0'
gem 'gmaps4rails'
gem 'googlecharts'
gem 'gravtastic'
gem 'haml-rails'
gem 'i18n-docs'
gem 'jquery-rails'
gem 'kaminari'
gem 'mini_magick'
gem 'money-rails'
gem 'octicons_helper'
gem 'paperclip'
gem 'paper_trail'
gem 'paranoia', '~> 2.0'
gem 'prawn-rails'
gem 'aws-sdk'
gem 'rqrcode_png'
gem 'sidekiq'
gem 'simple_form'
gem 'stripe', '4.22.0'
gem 'httparty'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

group :production, :staging do
  gem 'rails_12factor' # for Heroku
end

group :development, :test do
  gem 'faker', git: 'https://github.com/stympy/faker.git', branch: 'master'
  gem 'figaro'
  gem 'rspec-rails', '~> 3.0'
  gem 'factory_girl_rails'
  gem 'pry'
end
