source "http://rubygems.org"

gem 'chef',          "= 0.10.10"
gem 'ironfan',       "~> 3.1.5"

group :development do
  gem 'rake'
  gem 'bundler',     "~> 1"
  gem 'rspec',       "~> 2.5"
  gem 'yard',        "~> 0.6"

  gem 'ruby_gntp'

  gem 'guard'
  gem 'guard-process'
  gem 'guard-chef',    :git => 'git@github.com:infochimps-forks/guard-chef.git'
end

group :support do
  gem 'pry'  # useful in debugging
  gem 'grit' # used in rake scripts for push/pulling cookbooks
end
