source 'https://rubygems.org'

# Specify your gem's dependencies in grape-swagger-entity.gemspec
gemspec

gem 'grape-swagger', github: 'ruby-grape/grape-swagger'
gem 'danger', '~> 2.0', require: false unless RUBY_PLATFORM == 'java'

if RUBY_VERSION < '2.2.2'
  gem 'rack', '<2.0.0'
  gem 'activesupport', '<5.0.0'
end
