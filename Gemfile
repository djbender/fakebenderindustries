source 'https://rubygems.org'

gem 'rails', '4.2.1'
gem 'sqlite3'
# gem 'sass-rails', '~> 5.0'
# gem 'uglifier', '>= 1.3.0'
# gem 'coffee-rails', '~> 4.1.0'

# gem 'jquery-rails'
gem 'turbolinks'

# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

gem 'rack-mini-profiler'
gem 'flamegraph'

group :development do
  gem 'bullet'
  gem 'brakeman',       require: false
  gem 'guard-brakeman', require: false
  gem 'guard-rubocop',  require: false
  gem 'rubocop-rspec',  require: false
  gem 'guard-rspec',    require: false
  gem 'stackprof',      require: false
end

group :development, :test do
  gem 'rspec-rails'
  gem 'byebug'
  gem 'web-console', '~> 2.0'
  gem 'spring'
end
