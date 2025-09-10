source 'https://rubygems.org'
gemspec

gem 'simplecov', :require => false

gem 'pry-nav'
gem 'pry-rescue'

# optional dependency for more accurate timezone conversion
gem 'tzinfo', '1.2.5'
# gem 'tzinfo', '2.0.0'

# required for CircleCI to build properly with ruby 1.9.3
gem 'json', '~> 1.8.3'
gem 'rack', '~> 1.6.4'

if RUBY_VERSION >= '3.1.0'
  # Savon v2.13 adds a dependency on mail, which has an implicit dependency on
  # net-smtp. Ruby 3.1 removed net-smtp as a default gem. mail v2.8.0.rc1 is the
  # first to make that dependency explicit to support Ruby 3.1.
  gem 'mail', '>= 2.8.0.rc1'
end
