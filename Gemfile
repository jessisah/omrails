source 'https://rubygems.org'
ruby '2.0.0'


gem 'rails', '3.2.8'
gem 'jquery-rails'


# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

group :production do
	gem 'pg'
	gem 'rails_12factor'
end
group :development, :test do
	gem	'sqlite3'
end

# Gems used only for assets and not required
# in production environments by default.

group :assets do
    gem 'sass-rails',   '~> 3.2.3'
    gem 'coffee-rails', '~> 3.2.1'
	gem 'uglifier', '>= 1.0.3'
    gem 'bootstrap-sass', '~> 2.3.2.1'
    gem 'jbuilder', '~> 1.2'
end
group :doc do
	#bundle exec rake doc:rails generates the API under doc/api/
	gem 'sdoc', require: false
end


# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
