source 'https://rubygems.org'

# Specify your gem's dependencies in elementary-rpc.gemspec
gemspec

gem 'faraday'
gem 'rack'
gem 'protobuf', :github => 'lookout/protobuf',
                :ref => 'wip/http'

group :test do
  gem 'rspec'
end

group :development do
  gem 'pry'
  gem 'debugger', :platform => :mri
  gem 'debugger-pry', :platform => :mri
end
