source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.7.1'
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 2.7.2'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails', '>= 4.0.4'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Fix vulnerability CVE-2018-1000201
gem 'ffi', '~> 1.9.24'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '>= 2.1.3'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-commands-rspec'
  gem 'spring-commands-cucumber'

  gem 'rspec'
  gem 'cucumber', '>= 2.0.0'

  # specify version of aruba to include rspec integration
  gem 'aruba', git: 'https://github.com/cucumber/aruba', ref: '51cf61ed9e'
  gem 'rspec-rails'

  # version of cucumber-rails chosen to fix 
  # "invalid option: --no-profile" error referenced here:
  # https://github.com/netzpirat/guard-cucumber/issues/42
  gem 'cucumber-rails', require: false, ref: '11608dbef7', git: 'https://github.com/cucumber/cucumber-rails'
  gem 'guard'
  gem 'guard-rspec'
  gem 'guard-cucumber'
  gem 'terminal-notifier-guard'

  gem 'database_cleaner'

  # Hold rake at below 11.0 - https://stackoverflow.com/questions/35893584/nomethoderror-undefined-method-last-comment-after-upgrading-to-rake-11
  gem 'rake', '< 11.0'

  gem 'loofah', '>= 2.2.3'
end

