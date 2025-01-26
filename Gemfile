source "https://rubygems.org"

gem "rails", "~> 8.0.1"
gem "propshaft"
gem "puma", ">= 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "bootsnap", require: false
gem 'solid_queue'

group :development, :test do
  gem 'sqlite3', '~> 2.1'
  gem "debug", platforms: %i[mri windows], require: "debug/prelude"
  gem "brakeman", require: false
  gem "rubocop-rails-omakase", require: false
end

group :development do
  gem "web-console"
  gem "pg", "~> 1.1"
end

group :production do
  gem "pg", "~> 1.1"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
end
