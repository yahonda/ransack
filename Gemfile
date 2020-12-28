source 'https://rubygems.org'
gemspec

gem 'rake'
gem 'faker', '~> 1.0'
gem 'sqlite3', '~> 1.4.1'
gem 'pg', '~> 1.0'
gem 'mysql2', '~> 0.5.2'
gem 'pry', '~> 0.12.2'
gem 'byebug'

git 'https://github.com/rails/rails.git', :branch => 'master' do
  gem 'activesupport'
  gem 'activemodel'
  gem 'activerecord', require: false
  gem 'actionpack'
end

group :test do
  gem 'machinist', '~> 1.0.6'
  gem 'rspec', '~> 3'
  gem 'simplecov', :require => false
end

group :rubocop do
  # RuboCop 0.81.0 is the last version which supports Ruby 2.3.
  # Once Ransack required_ruby_version is bumped, RuboCop version can be bumped.
  # https://github.com/rubocop-hq/rubocop/pull/7869
  gem 'rubocop', '=0.81.0', require: false
end
