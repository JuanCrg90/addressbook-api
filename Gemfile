source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.1.5'
gem 'sqlite3'
gem 'puma', '~> 3.7'

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]

  gem 'factory_bot_rails'
  gem 'rspec-rails', '~> 3.7.0'
  gem 'rspec-rails-swagger', '~> 0.1.4'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'database_cleaner'
end

gem 'tzinfo-data', platforms: %I[mingw mswin x64_mingw jruby]