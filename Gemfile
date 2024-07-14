source 'https://rubygems.org'
ruby "2.1.5"

gem 'rails', '5.0.0'
gem 'rails-i18n', '~> 4.0.2'
gem 'i18n', '~> 0.6.11'

# Patched version. See http://rubysec.com/advisories/CVE-2015-5312/.
gem 'nokogiri', '>= 1.16.5'

gem 'pg'
gem 'spree', github: 'openfoodfoundation/spree', branch: '1-3-stable'
gem 'spree_i18n', github: 'spree/spree_i18n', branch: '1-3-stable'
gem 'spree_auth_devise', github: 'spree/spree_auth_devise', branch: '1-3-stable'

# Our branch contains two changes
# - Pass customer email and phone number to PayPal (merged to upstream master)
# - Change type of password from string to password to hide it in the form
gem 'spree_paypal_express', :github => "openfoodfoundation/better_spree_paypal_express", :branch => "hide-password"
#gem 'spree_paypal_express', :github => "spree-contrib/better_spree_paypal_express", :branch => "1-3-stable"

gem 'delayed_job_active_record'
gem 'daemons'
gem 'comfortable_mexican_sofa', '>= 1.6.25'

# Fix bug in simple_form preventing collection_check_boxes usage within form_for block
# When merged, revert to upstream gem
gem 'simple_form', :github => 'RohanM/simple_form'

gem 'unicorn', '>= 5.0.0'
gem 'angularjs-rails', '1.2.13'
gem 'bugsnag'
gem 'newrelic_rpm'
gem 'haml'
gem 'sass', "~> 3.3"
gem 'sass-rails', '~> 5.0.5', groups: [:default, :assets]
gem 'redcarpet'
gem 'aws-sdk', '>= 1.27.0'
gem 'db2fog', '>= 0.9.0'
gem 'andand'
gem 'truncate_html'
gem 'representative_view', '>= 1.2.3'
gem 'rabl'
gem "active_model_serializers"
gem 'oj'
gem 'deface', :github => 'spree/deface', :ref => '1110a13'
gem 'paperclip'
gem 'dalli'
gem 'geocoder'
gem 'gmaps4rails'
gem 'spinjs-rails', '>= 1.4'
gem 'rack-ssl', '>= 1.4.0', :require => 'rack/ssl'
gem 'custom_error_message', :github => 'jeremydurham/custom-err-msg'
gem 'angularjs-file-upload-rails', '~> 1.1.0'
gem 'roadie-rails', '~> 1.0.5'
gem 'figaro', '>= 1.0.0'
gem 'blockenspiel'
gem 'acts-as-taggable-on', '~> 3.4'
gem 'paper_trail', '~> 3.0.8'
gem 'diffy'

gem 'wicked_pdf', '>= 1.0.0'
gem 'wkhtmltopdf-binary'

gem 'foreigner'
gem 'immigrant'

gem 'whenever', require: false

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'compass-rails', '>= 3.0.0'
  gem 'coffee-rails', '~> 4.1.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer'

  gem 'uglifier', '>= 1.0.3'

  gem 'turbo-sprockets-rails3', '>= 0.3.7'
  gem 'foundation-icons-sass-rails'
  gem 'momentjs-rails', '>= 2.6.0'
  gem 'angular-rails-templates', '~> 1.0.0'
end

gem "foundation-rails", ">= 5.5.1.0"
gem 'foundation_rails_helper', github: 'willrjmarshall/foundation_rails_helper', branch: "rails3"

gem 'jquery-rails', '>= 4.0.1'
gem 'css_splitter', '>= 0.4.2'


group :test, :development do
  # Pretty printed test output
  gem 'turn', '~> 0.8.3', :require => false
  gem 'fuubar'
  gem 'rspec-rails', '>= 2.14.1'
  gem 'shoulda-matchers'
  gem 'factory_girl_rails', '>= 3.4.0', :require => false
  gem 'capybara', '>= 2.6.0'
  gem 'database_cleaner', '0.7.1', :require => false
  gem 'awesome_print'
  gem 'letter_opener'
  gem 'timecop'
  gem 'poltergeist', '>= 1.8.0'
  gem 'rspec-retry'
  gem 'json_spec'
  gem 'unicorn-rails', '>= 2.0.0'
  gem 'atomic'
  gem 'knapsack'
end

group :test do
  gem 'webmock'

  # See spec/spec_helper.rb for instructions
  #gem 'perftools.rb'
end

group :development do
  gem 'pry-byebug'
  gem 'debugger-linecache'
  gem 'guard'
  gem 'guard-livereload'
  gem 'rack-livereload', '>= 0.3.16'
  gem 'guard-rails'
  gem 'guard-zeus'
  gem 'guard-rspec'
  gem 'parallel_tests'
end
