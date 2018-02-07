source 'https://rubygems.org'
ruby '2.4.2'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'bootstrap-sass', '~> 3.3', '>= 3.3.7'
gem 'acts_as_votable', '~> 0.11.1'
gem 'simple_form', '~> 3.5'
gem 'record_tag_helper', '~> 1.0'

gem 'rails', '~> 5.1.4'
gem 'sqlite3'
gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'devise', '~> 4.4'
gem 'bcrypt', git: 'https://github.com/codahale/bcrypt-ruby.git', :require => 'bcrypt'

group :development, :test do 
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]  
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

group :development do 
  gem 'web-console', '>= 3.3.0'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
