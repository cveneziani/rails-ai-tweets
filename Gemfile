source "https://rubygems.org"

ruby "3.2.2"

# defaults
gem "rails", "~> 7.1.5", ">= 7.1.5.2"
gem "sprockets-rails"
gem "pg", "~> 1.1"
gem "puma", ">= 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ windows jruby ]
gem "bootsnap", require: false

# frontend
gem "bootstrap", "~> 5.3"
gem "autoprefixer-rails"
gem "font-awesome-sass", "~> 6.1"
gem "simple_form", github: "heartcombo/simple_form"
gem "sassc-rails"

# own gems
gem "ruby_llm", "~> 1.2.0"

group :development, :test do
  gem "dotenv-rails"
  gem "debug", platforms: %i[ mri windows ]
end

group :development do
  gem "web-console"


end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
end
