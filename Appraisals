appraise "rails-5.0" do
  gem 'rails', '~> 5.0.0'
  gem 'sass-rails', '~> 5.0'
  gem 'devise', '~> 4.0'

  group :test do
    gem 'cancancan', '~> 2.0'
  end

  group :active_record do
    gem 'paper_trail', '>= 5.0'

    platforms :jruby do
      gem 'activerecord-jdbcmysql-adapter', '~> 50.0'
      gem 'activerecord-jdbcpostgresql-adapter', '~> 50.0'
      gem 'activerecord-jdbcsqlite3-adapter', '~> 50.0'
    end
  end

  group :mongoid do
    gem 'mongoid', '~> 6.1'
    gem 'kaminari-mongoid'
    gem 'mongoid-paperclip', '>= 0.0.8', require: 'mongoid_paperclip'
    gem 'carrierwave-mongoid', '>= 0.6.3', require: 'carrierwave/mongoid'
    gem 'cancancan-mongoid'
  end
end

appraise "rails-5.1" do
  gem 'rails', '~> 5.1.0'
  gem 'sass-rails', '~> 5.0'
  gem 'devise', '~> 4.0'

  group :test do
    gem 'cancancan', '~> 2.0'
  end

  group :active_record do
    gem 'pg', '~> 0.14', platforms: :ruby
    gem 'paper_trail', '>= 5.0'

    platforms :jruby do
      gem 'activerecord-jdbcmysql-adapter', '~> 51.0'
      gem 'activerecord-jdbcpostgresql-adapter', '~> 51.0'
      gem 'activerecord-jdbcsqlite3-adapter', '~> 51.0'
    end
  end

  group :mongoid do
    gem 'mongoid', '~> 7.0'
    gem 'kaminari-mongoid'
    gem 'mongoid-paperclip', '>= 0.0.8', require: 'mongoid_paperclip'
    gem 'carrierwave-mongoid', '>= 0.6.3', require: 'carrierwave/mongoid'
    gem 'cancancan-mongoid'
  end
end

appraise "rails-5.2" do
  gem 'rails', '~> 5.2.0'
  gem 'sass-rails', '~> 5.0'
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
  end
end

appraise "cancan" do
  gem 'rails', '~> 5.1.0'
  gem 'sass-rails', '~> 5.0'
  gem 'devise', '~> 4.0'

  group :test do
    gem 'cancan', '>= 1.6'
  end
end
