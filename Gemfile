source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.3'

gem 'rails', '~> 6.1.7'
gem "nokogiri"
gem 'pg'
gem 'puma'#, '~> 4.1'
gem 'sass-rails'#, '>= 6'
gem 'webpacker'#, '~> 5.4'
gem 'bootsnap', '>= 1.4.2', require: false
gem "react-rails"#, "~> 2.6"
gem "devise"
gem "faker"
gem 'validates_timeliness', '~> 5.0.0.alpha3'
gem "simple_form"
gem "chartkick"
gem "rubyzip"
gem "zipline"
gem "googlebooks"

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'better_errors', '~> 2.1', '>= 2.1.1'
  gem 'pry'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem "dockerfile-rails", ">= 1.5", :group => :development

gem "sentry-ruby", "~> 5.10"

gem "sentry-rails", "~> 5.10"
