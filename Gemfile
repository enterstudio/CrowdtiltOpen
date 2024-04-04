source 'https://rubygems.org'
ruby '1.9.3'

# Framework and core dependencies
gem 'rails', '7.0.8.1'
gem 'pg'
gem 'unicorn', '>= 4.6.3'
gem 'foreman'

gem 'crowdtilt', github: 'Crowdtilt/crowdtilt-gem'
gem 'devise', '~> 4.7.0'
gem 'nokogiri', '>= 1.15.6'
gem 'friendly_id', '~> 4.0.9'
gem 'iso_country_codes'
gem 'paperclip', '~> 3.0'
gem 'ckeditor'
gem 'aws-sdk', '>= 1.11.1'
gem 'active_model_serializers'
gem 'momentjs-rails', '>= 2.5.1'
# Front-end
gem 'bootstrap-sass', '2.1'
gem 'jquery-rails', '>= 4.0.1'
gem 'jquery-ui-rails', '>= 4.0.4'

group :production do
  gem 'newrelic_rpm'
  gem 'lograge', '>= 0.3.0'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', '~> 5.0.8'
  gem 'coffee-rails', '~> 4.2.2'
  gem 'uglifier', '>= 1.0.3'
  gem 'asset_sync', '>= 1.0.0'
end

group :development, :test do
  gem 'pry-rails'
  gem 'rspec-rails', '>= 2.14.0'
  gem 'factory_girl_rails', '>= 4.3.0'
  gem 'shoulda'
end

group :development do
  gem 'quiet_assets', '>= 1.0.3'
end

group :test do
  gem 'faker'
  gem 'capybara', '>= 2.2.0'
  gem 'email_spec'
end
