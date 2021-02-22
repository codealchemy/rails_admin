appraise "rails-5.2" do
  gem 'rails', '~> 5.2.0'
  gem 'sassc-rails', '~> 2.1'
  gem 'devise', '~> 4.4'

  group :test do
    gem 'cancancan', '~> 2.0'
  end

  group :active_record do
    gem 'pg', '>= 1.0.0', platforms: :ruby
    gem 'paper_trail', '>= 5.0'

    platforms :jruby do
      gem 'activerecord-jdbcmysql-adapter', '~> 52.0'
      gem 'activerecord-jdbcpostgresql-adapter', '~> 52.0'
      gem 'activerecord-jdbcsqlite3-adapter', '~> 52.0'
    end
  end

  group :mongoid do
    gem 'mongoid', '~> 7.0'
    gem 'kaminari-mongoid'
    gem 'mongoid-paperclip', '>= 0.0.8', require: 'mongoid_paperclip'
    gem 'carrierwave-mongoid', '>= 0.6.3', require: 'carrierwave/mongoid'
    gem 'cancancan-mongoid'
    gem 'shrine-mongoid'
  end
end

appraise "rails-6.0" do
  gem 'rails', '~> 6.0.0'
  gem 'haml'
  gem 'sassc-rails', '~> 2.1'
  gem 'devise', '~> 4.7'

  group :test do
    gem 'cancancan', '~> 3.0'
    gem 'rspec-rails', '>= 4.0.0.beta2'
  end

  group :active_record do
    gem 'pg', '>= 1.0.0', platforms: :ruby
    gem 'paper_trail', '>= 5.0'

    platforms :jruby do
      gem 'activerecord-jdbcmysql-adapter', '~> 60.0'
      gem 'activerecord-jdbcpostgresql-adapter', '~> 60.0'
      gem 'activerecord-jdbcsqlite3-adapter', '~> 60.0'
    end
  end

  group :mongoid do
    gem 'mongoid', '~> 7.0'
    gem 'kaminari-mongoid'
    gem 'mongoid-paperclip', '>= 0.0.8', require: 'mongoid_paperclip'
    gem 'carrierwave-mongoid', '>= 0.6.3', require: 'carrierwave/mongoid'
    gem 'cancancan-mongoid'
    gem 'shrine-mongoid'
  end
end

appraise "rails-6.1" do
  gem 'rails', '~> 6.1.0.rc1'
  gem 'haml'
  gem 'sassc-rails', '~> 2.1'
  gem 'devise', '~> 4.7'

  group :test do
    gem 'cancancan', '~> 3.0', github: 'ghiculescu/cancancan', branch: 'avoid-resolve_column_aliases-2'
    gem 'rspec-rails', '>= 4.0.0.beta2'
  end

  group :active_record do
    gem 'pg', '>= 1.0.0', platforms: :ruby
    gem 'paper_trail', '>= 5.0'
  end
end
