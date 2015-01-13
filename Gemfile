source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.0'
ruby '2.0.0'
group :production do
     gem "rails_12factor"
     gem "pg"
end
group :development, :test do
     gem "sqlite3"
     # Helpful gems
     gem "better_errors" # improves error handling
     gem "binding_of_caller" # used by better errors
     # Testing frameworks
     gem 'rspec-rails' # testing framework
     gem "factory_girl_rails" # use factories, not fixtures
     gem "capybara" # simulate browser activity
     gem "fakeweb"
     # Automated testing
     gem 'guard' # automated execution of test suite upon change
     gem "guard-rspec" # guard integration with rspec
     # Only install the rb-fsevent gem if on Max OSX
     gem 'rb-fsevent' # used for Growl notifications
end
gem 'sass-rails', '~> 5.0'
gem "execjs"
gem "twitter-bootstrap-rails"
gem "bootstrap-sass"
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc

# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'


end



