source 'https://rubygems.org'
ruby '1.9.3'

# Framework and core dependencies
gem 'rails', '5.2.6.2'
gem 'pg'
gem 'unicorn'
gem 'foreman'

gem 'crowdtilt', github: 'Crowdtilt/crowdtilt-gem'
gem 'devise', '~> 4.4.2'
gem 'nokogiri'
gem 'friendly_id', '~> 4.0.9'
gem 'iso_country_codes'
gem 'paperclip', '~> 3.0'
gem 'ckeditor'
gem 'aws-sdk'
gem 'active_model_serializers'
gem 'momentjs-rails', '>= 2.5.0'
# Front-end
gem 'bootstrap-sass', '2.1'
gem 'jquery-rails', '>= 4.0.1'
gem 'jquery-ui-rails', '>= 4.0.3'

group :production do
  gem 'newrelic_rpm'
  gem 'lograge', '>= 0.2.2'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', '~> 5.0.5'
  gem 'coffee-rails', '~> 4.2.2'
  gem 'uglifier', '>= 1.0.3'
  gem 'asset_sync'
end

group :development, :test do
  gem 'pry-rails'
  gem 'rspec-rails', '>= 2.13.2'
  gem 'factory_girl_rails', '>= 4.2.1'
  gem 'shoulda'
end

group :development do
  gem 'quiet_assets'
end

group :test do
  gem 'faker'
  gem 'capybara'
  gem 'email_spec'
end
