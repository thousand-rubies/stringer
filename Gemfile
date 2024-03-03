ruby_version_file = File.expand_path(".ruby-version", __dir__)
ruby File.read(ruby_version_file).chomp if File.readable?(ruby_version_file)
source "https://rubygems.org"

group :development do
  gem "rubocop", require: false
  gem "rubocop-rails", ">= 2.17.0", require: false
  gem "rubocop-rake", require: false
  gem "rubocop-rspec", require: false
end

group :development, :test do
  gem "capybara", ">= 3.38.0"
  gem "coveralls_reborn", require: false
  gem "faker"
  gem "pry-byebug"
  gem "rack-test", ">= 2.1.0"
  gem "rspec"
  gem "rspec-html-matchers"
  gem "shotgun"
  gem "simplecov"
  gem "timecop"
end

gem "activerecord", ">= 7.0.7.1"
gem "bcrypt"
gem "delayed_job"
gem "delayed_job_active_record", ">= 4.1.8"
gem "feedbag"
gem "feedjira", ">= 3.2.2"
gem "httparty", ">= 0.21.0"
gem "i18n"
gem "loofah", ">= 2.19.1"
gem "nokogiri", ">= 1.16.2"
gem "pg"
gem "puma", ">= 5.6.8"
gem "rack-protection", ">= 3.0.3"
gem "racksh", ">= 1.0.1"
gem "rack-ssl"
gem "rake"
gem "sass"
gem "sinatra", ">= 4.0.0"
gem "sinatra-activerecord", ">= 2.0.26"
gem "sinatra-contrib", ">= 4.0.0"
gem "sinatra-flash"
gem "sprockets", ">= 4.2.0"
gem "sprockets-helpers"
gem "thread"
gem "uglifier"
gem "will_paginate"
