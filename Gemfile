source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.4.1'

gem 'bootsnap', '>= 1.1.0', require: false
gem 'faraday'
gem 'figaro'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.12'
gem 'rack-cors'
gem 'rails', '~> 5.2.3'
gem 'twilio-ruby', '~> 5.25.1'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'factory_bot_rails'
  gem 'faker', :git => 'https://github.com/stympy/faker.git', :branch => 'master'
  gem 'pry'
  gem 'rspec-rails'
  gem 'rspec_junit_formatter'
  gem 'vcr'
  gem 'simplecov'
  gem 'shoulda-matchers'
  gem 'webmock'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end


# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
