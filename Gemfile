source 'https://rubygems.org'
git_source(:github) { |repo_name| "https://github.com/#{repo_name}.git" }

gem 'rails', '~> 5'

# https://github.com/rails/sprockets-rails/issues/131
# gem 'sprockets-rails', :require => 'sprockets/rails/version'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3', '~> 1.3.6' # ActiveRecord needs this version

gem 'bootstrap', '~> 4.3'
gem 'coffee-rails'
gem 'sassc-rails'

gem 'uglifier', '>= 1.0.3'

gem 'autoprefixer-rails'
gem 'bootsnap'
gem 'favicon_maker'
gem 'formtastic'
gem 'formtastic-bootstrap'
gem 'git_rev'
gem 'gravatar_image_tag'
gem 'haml-rails'
gem 'jquery-rails'
gem 'mini_magick'
gem 'paperclip'
gem 'puma'
gem 'rails-controller-testing'

gem 'codeclimate-test-reporter', '~> 1', group: :test, require: nil

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# To use debugger
# gem 'debugger'
#
#
gem 'sentry-raven'

group :development do
  gem 'faker'
  gem 'minitest', '< 5.11'
  gem 'rails-perftest'
  gem 'rubocop', '~> 0.72.0', require: false
  gem 'ruby-prof'
  gem 'spring'
end

group :production do
  gem 'pg'
  gem 'SyslogLogger'
end
