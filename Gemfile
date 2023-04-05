source 'https://rubygems.org'
ruby '1.9.3'

# Framework and core dependencies
gem 'rails', '6.1.7.3'
gem 'pg'
gem 'unicorn'
gem 'foreman'

gem 'crowdtilt', github: 'Crowdtilt/crowdtilt-gem'
gem 'devise', '~> 4.7.1'
gem 'nokogiri', '>= 1.13.9'
gem 'friendly_id', '~> 4.0.9'
gem 'iso_country_codes'
gem 'paperclip', '~> 5.2', '>= 5.2.1'
gem 'ckeditor'
gem 'aws-sdk', '>= 1.52.0'
gem 'active_model_serializers'
gem 'momentjs-rails'
# Front-end
gem 'bootstrap-sass', '3.4.0'
gem 'jquery-rails', '>= 4.4.0'
gem 'jquery-ui-rails', '>= 6.0.0'

group :production do
  gem 'newrelic_rpm'
  gem 'lograge'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', '~> 5.0.8'
  gem 'coffee-rails', '~> 4.2.2'
  gem 'uglifier', '>= 2.7.2'
  gem 'asset_sync'
end

group :development, :test do
  gem 'pry-rails'
  gem 'rspec-rails'
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
