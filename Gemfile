source 'https://rubygems.org'
ruby '2.3.0'

gem 'bootstrap-sass'
gem 'coffee-rails'
gem 'rails', '4.2.6'
gem 'haml-rails'
gem 'sass-rails'
gem 'uglifier'
gem 'jquery-rails'
gem 'pg'
gem 'pg_search'
gem 'bootstrap_form'
gem 'bcrypt-ruby'
gem 'sidekiq'
gem "figaro"
gem 'carrierwave'
gem 'mini_magick'
gem 'carrierwave-aws'
gem 'stripe'
gem 'stripe_event'
gem 'draper'
#gem 'elasticsearch-model'
#gem 'elasticsearch-rails'

group :development do
  gem 'thin'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'letter_opener'
end

group :development, :test do
  gem 'pry'
  gem 'pry-nav'
  gem 'rspec-rails' 
  gem 'faker'
  gem 'fabrication'
end

group :test do
  gem 'database_cleaner', '1.4.1'
  gem 'launchy'
  gem 'shoulda-matchers'
  gem 'capybara'
  gem 'capybara-email'
  gem 'vcr'
  gem 'webmock'
  gem 'poltergeist'
end

group :production do
  gem 'rails_12factor'
  gem 'unicorn'
  gem "sentry-raven" #, :github => "getsentry/raven-ruby"
end

