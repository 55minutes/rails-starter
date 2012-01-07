source 'http://rubygems.org'

gem 'bcrypt-ruby', '~> 3.0.0'
gem 'jquery-rails'
gem 'pg'
gem 'rails',       '3.1.3'
# gem 'ruby-debug19', :require => 'ruby-debug'


# Gems used only for assets and not required
# in production environments by default.
#
group :assets do
  gem 'compass',      '>= 0.12.alpha.1'
  gem 'sass-rails',   '~> 3.1.5'
  gem 'coffee-rails', '~> 3.1.1'
  gem 'uglifier',     '>= 1.0.3'
end

# Gems that facilitate development but are not required to run the app.
# Note `:require => false` for those gems that are purely command-line tools.
#
group :development do
  gem 'capistrano',  '~> 2.5.19', :require => false
  gem 'rb-fsevent',               :require => false
  gem 'guard-rspec',              :require => false
  gem 'ruby_gntp',                :require => false
  gem 'thin',                     :require => false
end

# Gems needed for running tests.
# Note that some of these are also used in :development for Rails generators.
#
group :test do
  gem 'factory_girl_rails',             :group => :development
  gem 'launchy'
  gem 'steak',                          :group => :development
  gem 'turn',               '~> 0.8.3', :require => false
end