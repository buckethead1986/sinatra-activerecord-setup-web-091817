# A sample Gemfile
source "https://rubygems.org"

gem 'sinatra'
gem 'thin'
gem 'require_all'
gem 'activerecord', '4.2.5' #fucking. magic. database mapping and object relationship/association power
gem 'sinatra-activerecord' #gives a bunch of awesome ruby tasks
gem 'rake' #short for 'ruby-make', lets you cretae files, folders, and automate things like database creation.


group :development do #wont get installed on the server when the application is deployed. Just for use in development :D
	gem 'shotgun'
	gem 'pry'
	gem 'sqlite3' #database adapter gem, allows communication with a sql database
	gem 'tux' #gives interactive console that preloads database and activerecords relationships for you
end

group :test do
  gem 'rspec'
  gem 'capybara'
  gem 'rack-test'
end
