source 'http://rubygems.org'

gemspec

# apps can also use will_paginate so there's no dependency in gemspec
gem 'kaminari'

# gem 'comfortable_mexican_sofa', :github => 'comfy/comfortable-mexican-sofa', :branch => '2.0'


group :development do

  gem 'awesome_print'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'quiet_assets'
end

group :test do
  gem 'sqlite3',                          :platform => [:ruby, :mswin, :x64_mingw]
  gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw]
  gem 'jdbc-sqlite3',                     :platform => :jruby
  gem 'activerecord-jdbcsqlite3-adapter', :platform => :jruby
  gem 'mocha',      :require => false
  gem 'coveralls',  :require => false
end