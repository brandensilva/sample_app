source 'https://rubygems.org'
ruby '1.9.3'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'
gem 'bootstrap-sass', '2.3.2.0'

group :development, :test do
	gem 'sqlite3', '1.3.7'
	gem 'rspec'
	gem 'rspec-rails', '2.13.1'
	gem 'guard-rspec', '2.5.0'
	gem 'spork-rails', github: 'sporkrb/spork-rails'
	gem 'guard-spork', '1.5.0'
	gem 'childprocess', '0.3.9'
end

group :test do
	gem 'selenium-webdriver', '2.0.0'
	gem 'capybara', '2.1.0'
	gem 'rb-notifu', '0.0.4'
	gem 'win32console', '1.3.2'
	require 'rbconfig'
	gem 'wdm', '0.1.0' if RbConfig::CONFIG['target_os'] =~ /mswin|mingw/i
end

gem 'sass-rails', '4.0.0'
gem 'uglifier', '2.1.1'
gem 'coffee-rails', '4.0.0'
gem 'jquery-rails', '2.2.1'
gem 'turbolinks', '1.1.1'
gem 'jbuilder', '1.0.2'

group :doc do
  gem 'sdoc', '0.3.20', require: false
end

group :production do
	gem 'pg', '0.15.1'
	gem 'rails_12factor', '0.0.2'
end