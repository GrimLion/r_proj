source 'https://rubygems.org'

# you are using Ruby 1.9.3, better to 2.0.0 upgrade for more speed
#ruby '2.0.0'

gem 'rails'   
gem 'sass-rails'  
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks'    
gem 'jbuilder'

# The asset_sync gem is WELL worth using
# but you should read more about it before deciding
# https://github.com/rumblelabs/asset_sync
# gem 'asset_sync'

# only want sqlite in dev and test envs
group :development do
  gem 'sqlite3'
  gem 'rspec-rails'
  gem 'guard-rspec'
end

group :test do
	gem 'rspec-rails'
	gem 'capybara'
	gem 'rb-inotify'
	gem 'libnotify'
	gem 'guard-spork'
	gem 'spork'
end

group :production do
  gem 'pg' # dont want sqlite in production
  gem 'unicorn' # make sure you follow installation instructions for this gem
  gem 'rails_log_stdout',           github: 'heroku/rails_log_stdout'
  gem 'rails3_serve_static_assets', github: 'heroku/rails3_serve_static_assets'
end
