source 'https://rubygems.org'

gem 'appraisal', '>= 2.0'
gem 'rails'
gem 'haml'
gem 'devise'

group :active_record do
  gem 'paper_trail'

  platforms :ruby, :mswin, :mingw, :x64_mingw do
    gem 'mysql2', '>= 0.3.14'
    gem 'sqlite3', '>= 1.3'
  end
end

group :development, :test do
  gem 'pry', '>= 0.9'
end

group :test do
  gem 'cancancan', '~> 3.0'
  gem 'carrierwave', ['>= 2.0.0.rc', '< 3']
  gem 'database_cleaner-mongoid', '>= 2.0', require: false
  gem 'database_cleaner-active_record', '>= 2.0', require: false
  gem 'dragonfly', '~> 1.0'
  gem 'factory_bot', '>= 4.2'
  gem 'generator_spec', '>= 0.8'
  gem 'launchy', '>= 2.2'
  gem 'mini_magick', '>= 3.4'
  gem 'paperclip', ['>= 3.4', '!= 4.3.0']
  gem 'poltergeist', '~> 1.5'
  gem 'pundit'
  gem 'rack-cache', require: 'rack/cache'
  gem 'rspec-rails', '>= 2.14'
  gem 'rspec-expectations', '!= 3.8.3'
  gem 'rspec-retry'
  gem 'rubocop', '~> 0.68.1'
  gem 'rubocop-performance'
  gem 'simplecov', '>= 0.9', require: false
  gem 'simplecov-lcov', require: false
  gem 'shrine', '~> 2.0'
  gem 'shrine-memory'
  gem 'timecop', '>= 0.5'

  # Windows does not include zoneinfo files, so bundle the tzinfo-data gem
  gem 'tzinfo-data', platforms: %i(mingw mswin x64_mingw jruby)
end

gemspec
