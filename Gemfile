source 'https://rubygems.org'
ruby '1.9.3'

# Framework and core dependencies
gem 'rails', '4.0.0'
gem 'pg'
gem 'unicorn', '>= 5.1.0'
gem 'foreman'

gem 'crowdtilt', github: 'Crowdtilt/crowdtilt-gem'
gem 'devise', '~> 4.0.0'
gem 'nokogiri'
gem 'friendly_id', '~> 4.0.9'
gem 'iso_country_codes'
gem 'paperclip', '~> 3.0'
gem 'ckeditor'
gem 'aws-sdk'
gem 'active_model_serializers'
gem 'momentjs-rails'
# Front-end
gem 'bootstrap-sass', '2.1'
gem 'jquery-rails', '>= 4.0.0'
gem 'jquery-ui-rails', '>= 4.0.5'

group :production do
  gem 'newrelic_rpm'
  gem 'lograge', '>= 0.4.0'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', '~> 6.0.0'
  gem 'coffee-rails', '~> 4.0.0'
  gem 'uglifier', '>= 1.0.3'
  gem 'asset_sync'
end

group :development, :test do
  gem 'pry-rails'
  gem 'rspec-rails', '>= 4.0.0'
  gem 'factory_girl_rails'
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
