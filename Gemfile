source 'https://rubygems.org'
ruby '2.3.0'

gem 'rails', '~> 4.2.5'
gem 'rails-api'
gem 'pg'
gem 'puma'
gem 'rack-timeout'

group :development do
  gem 'pry-rails'
  gem 'spring'
  gem 'bullet'
end

group :test do
  gem 'database_cleaner'
  gem 'rake'
end

group :development, :test do
  gem 'rspec-rails', '~> 3.0'
  gem 'factory_girl_rails'
  gem 'bundler-audit', require: false
end

group :production do
  gem 'rails_12factor'
end
