source "https://rubygems.org"

ruby "2.1.0"
gem "rails", "4.0.2"

gem "active_model_serializers", "0.8.1"
gem "haml-rails", "0.5.3"
gem "jquery-rails", "3.1.0"
gem "pg", "0.17.1"
gem "sass-rails", "4.0.1"
gem "settingslogic", "2.0.9"
gem "uglifier", "2.4.0"

group :production, :staging do 
  gem "rails_12factor", "0.0.2"
  gem "unicorn", "4.8.2"
end

group :development do
  gem "better_errors", "1.1.0"
  gem "binding_of_caller", "0.7.2"
end

group :development, :test do
  gem "brakeman", "2.4.0"
  gem "capybara", "2.2.1"
  gem "database_cleaner", "1.2.0"
  gem "factory_girl_rails", "4.4.0"
  gem "faker", "1.2.0"
  gem "figaro", "0.7.0"
  gem "fuubar", "1.3.2"
  gem "hakiri", "0.7.0"
  gem "pry-rails", "0.3.2"
  gem "pry-remote", "0.1.8"
  gem "rspec-rails", "2.14.1"
  gem "rubocop", "0.18.1"
  gem "shoulda", "3.5.0"
  gem "travis-lint", "1.7.0"
end