source 'https://rubygems.org'

gemspec

gem "administrate-field-image",
  git: "https://github.com/thoughtbot/administrate-field-image.git",
  branch: "jq-rails-5"
gem "bourbon", "5.0.0.beta.6"
gem "delayed_job_active_record"
gem "faker"
gem "high_voltage"
gem "markdown-rails", ">= 1.0.0"
gem "pg"
gem "redcarpet"
gem "unicorn"

group :development do
  gem "web-console", ">= 2.3.0"
end

group :development, :test do
  gem "appraisal"
  gem "awesome_print"
  gem "bundler-audit", require: false
  gem "byebug"
  gem "dotenv-rails", ">= 2.1.0"
  gem "factory_girl_rails", ">= 4.6.0"
  gem "i18n-tasks"
  gem "pry-rails"
  gem "rspec-rails", "~> 3.5.1"
end

group :test do
  gem "ammeter", ">= 1.1.4"
  gem "database_cleaner"
  gem "formulaic", ">= 0.4.0"
  gem "launchy"
  gem "poltergeist", ">= 1.8.0"
  gem "shoulda-matchers", "~> 2.8.0", require: false
  gem "timecop"
  gem "webmock"
end

group :staging, :production do
  gem "rack-timeout"
  gem "rails_stdout_logging"
  gem "uglifier"
end
