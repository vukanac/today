
source "https://rubygems.org"

gem "rails", "4.2.0"
gem "bcrypt-ruby", "3.1.5"

gem "pg"
gem "oj"
gem "bourbon"
gem "flutie"
gem "haml-rails"
gem "sass", "~> 3.4.9"
gem "bootstrap-sass", "~> 3.3.3"
gem "sass-rails"
gem "puma", "~> 2.10"
gem "foreman", require: false
gem "jquery-rails"
gem "clearance"

group :development do
  gem "spring"
  gem "spring-commands-rspec"
  gem "quiet_assets"
  gem "better_errors"
  gem "binding_of_caller"
end

group :development, :test do
  gem "factory_girl_rails"
  gem "rspec-rails", "~> 3.1.0"
  gem "simplecov", require: false
  gem "dotenv-rails"
end

group :development, :doc do
  gem "yard"
  gem "kramdown"
end

group :test do
  gem "shoulda-matchers", "~> 2.7.0", require: false
  gem "timecop"
end

group :production, :staging do
  gem "rack-timeout"
  gem "rails_12factor"
end
