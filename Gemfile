source 'https://rubygems.org'

# Specify your gem's dependencies in elementary-rpc.gemspec
gemspec

gem 'rack'
gem 'protobuffy', :github => 'lookout/protobuffy'

group :test do
  gem 'rspec'
end

group :development do
  gem 'pry'
  gem 'debugger', :platform => :mri_19
  gem 'debugger-pry', :platform => :mri_19
  gem 'byebug', :platform => [:mri_20, :mri_21]
end
