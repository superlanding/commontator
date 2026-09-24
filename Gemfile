source 'https://rubygems.org'

# Declare your gem's dependencies in commontator.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.

# To use debugger
gem 'byebug'

# Specify the Rails version for testing
gem *[ 'rails', ENV['RAILS_VERSION'] ].compact

# Reduces boot times through caching; required in spec/dummy/config/boot.rb
gem 'bootsnap', '>= 1.4.4', require: false

# Database adapters
gem 'sqlite3', require: false
gem 'mysql2', require: false
gem 'pg', require: false

# Code coverage
gem 'codeclimate-test-reporter', require: false
gem 'simplecov',                 require: false

# json 3.x removed quirks_mode; AS 8.0.x JSON encoder still passes it
gem 'json', '~> 2.7'

# concurrent-ruby 1.3.5+ breaks Rails < 7.1 (LoggerThreadSafeLevel::Logger)
gem 'concurrent-ruby', '1.3.4'
