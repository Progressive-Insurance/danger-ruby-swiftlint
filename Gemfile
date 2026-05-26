# frozen_string_literal: true

source 'https://rubygems.org'

gemspec

gem 'danger'
gem 'danger-rubocop'

group :development do
  gem 'bacon'
  gem 'bundler'
  gem 'mocha'
  gem 'mocha-on-bacon'
  # `parallel` 2.x requires Ruby >= 3.3 — keep it on 1.x so the matrix
  # can still install on Ruby 3.0–3.2.
  gem 'parallel', '< 2'
  gem 'prettybacon'
  gem 'rubocop', '~> 1.50', require: false
end
