source 'https://rubygems.org'

ruby '2.0.0'

gem 'airbrake'
gem 'bourbon'
gem 'delayed_job_active_record', '>= 4.0.0.beta2'
gem 'email_validator'
gem 'flutie'
gem 'high_voltage'
gem 'jquery-rails'
gem 'pg'
gem 'rack-timeout'
gem 'rails', '>= 4.0.0'
gem 'recipient_interceptor'
gem 'simple_form'
gem 'stripe', git: 'https://github.com/stripe/stripe-ruby'
gem 'unicorn'

group :assets do
  gem 'coffee-rails'
  gem 'sass-rails'
  gem 'uglifier'
end

group :development do
  gem 'foreman'
  gem 'better_errors'
  gem 'binding_of_caller'
end

group :development, :test do
  gem 'factory_girl_rails'
  gem 'rspec-rails'
  gem 'sham_rack'
end

group :test do
  gem 'bourne', require: false
  gem 'capybara-webkit', '>= 0.14.1'
  gem 'database_cleaner'
  gem 'launchy'
  gem 'shoulda-matchers'
  gem 'simplecov', require: false
  gem 'timecop'
end

group :staging, :production do
  gem 'newrelic_rpm', '>= 3.5.7'
  gem 'rails_12factor'
end
