source 'https://rubygems.org'

gem 'rails', require: nil
gem 'activerecord'
gem 'sqlite3'
gem 'sidekiq'

gem 'sentry-raven' # ,    github: 'getsentry/raven-ruby'
gem 'metriks'

gem 'nokogiri', '~> 1.6.6'
gem 'savon', '~> 2.11'

gem 'annotate', '~> 2.6.6'

gem 'strip_attributes', '~> 1.7.0'

gem 'rack'
gem 'rack-contrib'
gem 'sinatra', '~> 1.4.6', require: 'sinatra/base' # see https://github.com/resque/resque/issues/934
gem 'sinatra-contrib', '~> 1.4.4'

gem 'activesupport'

gem 'settingslogic', '~> 2.0.9'

if RUBY_PLATFORM =~ /win32|mingw32/
  gem 'thin'
else
  gem 'puma'
end

group :test, :development do
  gem 'rubocop'
  gem 'rspec'
  gem 'factory_girl'
  gem 'database_cleaner'
end
