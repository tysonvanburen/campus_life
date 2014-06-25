source 'https://rubygems.org'

gem 'rails', '4.1.1'
gem 'pg'
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0',          group: :doc
gem 'spring',        group: :development

# gems that are only used for testing
group :test do
  # rspec matchers collection of special matchers to test models
  gem 'shoulda-matchers'
  # cleans out our test database everytime we are done with our tests
  gem 'database_cleaner'
end

# gems that are only used for development and testing
group :development, :test do
  # generates fake data. user.. a radon email, address, phone number ..ect
  gem 'ffaker'
  gem 'rspec-rails'
  gem 'pry-rails'
  # allows you to create new records from your modles 
  gem 'factory_girl_rails'

end
