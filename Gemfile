source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.1'

gem 'rails', '~> 5.2.2'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.11'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'rack-cors', require: 'rack/cors'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'bootsnap', '>= 1.1.0', require: false
gem 'validate_url'

gem 'graphql', '1.8.13'
gem 'graphql-query-resolver'
gem 'search_object'
gem 'search_object_graphql'

gem 'bcrypt', '~> 3.1', '>= 3.1.12'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'factory_bot_rails'
  gem 'graphiql-rails'
  gem 'rubocop'
  gem 'rubocop-performance'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem "awesome_print", require:"ap"
  gem 'meta_request'
  gem "better_errors"
  gem "binding_of_caller"
  gem "pry-rails"
end

group :test do
  gem 'capybara', '>= 2.15'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
