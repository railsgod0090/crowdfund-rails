source 'https://rubygems.org'
ruby '2.3.1'

gem 'rails', '4.2.5'

# front-end
gem 'bootstrap-sass', '~> 3.3.6'
gem 'bourbon', '~> 4.2.3'
gem 'bower'
gem 'coffee-rails', '~> 4.1.0'
gem 'compass', '~> 1.0.3'
gem 'hamlit', '~> 2.2'
gem 'jquery-rails', '~> 4.0.5'
gem 'jquery-turbolinks', '~> 2.1.0'
gem 'nav_lynx', '~> 1.1.1'
gem 'sass-rails', '~> 5.0.4'
# gem 'sassc', '~> 1.8'
gem 'turbolinks', '~> 2.5.3'
gem 'uglifier', '>= 1.3.0'

# charts
gem 'groupdate'

# file handling
gem 'carrierwave', '~> 0.10.0'
gem 'mini_magick', '~> 4.3.6'

# security & auth
gem 'bcrypt', '~> 3.1.7'
gem 'cancancan', '~> 1.13.1'
gem 'has_secure_token', '~> 1.0.0'
gem 'sorcery', '~> 0.9.1'

# payment
gem 'stripe', '~> 1.31'

# search
gem 'elasticsearch-model', '~> 0.1.8'
gem 'elasticsearch-rails', '~> 0.1.8'

# cache
gem 'hiredis'
gem 'readthis', '~> 1.1' # cool new redis client http://sorentwo.com/2015/07/20/high-performance-caching-with-readthis.html

# mailers
gem 'mandrill-api', '~> 1.0.53'

# background jobs
gem 'sidekiq', '~> 4.0'

# miscelaneous
gem 'country_select', '~> 2.2.0'
gem 'countries'
gem 'figaro', '~> 1.1.1'
gem 'jbuilder', '~> 2.0'
gem 'kaminari', '~> 0.16.3'
gem 'redcarpet', '~> 3.3.2'
gem 'ruby-oembed', '~> 0.8.14'
gem 'sequenced'
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'social_shares', '~> 0.2.5'
gem 'tumblr_client', '~> 0.8.5'

# localization
gem 'rails-i18n', '~> 4.0.4'

# performance & monitoring
gem 'airbrake'
gem 'skylight', '~> 0.10.0'

# server & deployment
gem 'pg', '~> 0.18.4'
gem 'puma', '~> 2.15.3'

# benchmarking
gem 'stackprof', '~> 0.2.7'

group :development do
  gem 'better_errors'
  gem 'binding_of_caller', '~> 0.7.2'
  gem 'brakeman', '~> 3.1'
  gem 'bullet', '~> 4.14.7'
  gem 'derailed_benchmarks', '~> 1.0.1'
  gem 'gem_bench'
  gem 'letter_opener', '~> 1.4'
  gem 'memory_profiler', '~> 0.9.4'
  gem 'meta_request'
  gem 'populator', '~> 1.0.0'
  gem 'sinatra', '~> 1.4.6' # for Sidekiq monitoring https://github.com/mperham/sidekiq/wiki/Monitoring
  gem 'rails-footnotes', '~> 4.1.7'
  gem 'rails_best_practices'
end

group :development, :test do
  gem 'byebug'
  gem 'ffaker', '~> 2.1.0'
  gem 'rspec-rails', '~> 3.3.1'
  gem 'spring', '~> 1.3.6'
  gem 'web-console', '~> 2.0'
end

group :test do
  gem 'capybara', '~> 2.5.0'
  gem 'capybara-screenshot'
  gem 'capybara-webkit', '~> 1.11'
  gem 'codeclimate-test-reporter', require: nil
  gem 'database_cleaner', '~> 1.5.0'
  gem 'factory_girl_rails', '~> 4.5.0'
  gem 'guard-rspec', '~> 4.6.0'
  gem 'shoulda-matchers', '~> 3.0'
  gem 'webmock', '~> 1.22'
  gem 'vcr', '~> 3.0'
end

group :production do
  gem 'bonsai-elasticsearch-rails', '~> 0.0.4'
  gem 'fog', '~> 1.36'
  gem 'rails_12factor', '~> 0.0.3'
end
