source 'https://rubygems.org'

ruby '2.0.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0.beta1'

gem 'activerecord-postgres-earthdistance'
gem 'acts-as-taggable-on'
gem 'geocoder'
gem 'geokit'
gem 'haml-rails'
gem 'pg'
gem 'simple_form'
gem 'sorcery', git: 'git://github.com/NoamB/sorcery.git' # master branch for Rail 4

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 4.0.0.beta1'
  gem 'coffee-rails', '~> 4.0.0.beta1'
  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.0.1'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'letter_opener'
  gem 'pry'
  gem 'pry-awesome_print'
  gem 'quiet_assets'
  gem 'rails_view_annotator'
  gem 'thin'
end

group :test do
  gem 'factory_girl_rails'
  gem 'resque_spec'
  gem 'rspec-rails'
  gem 'rspec_candy'
  gem 'shoulda-matchers'
  gem 'simplecov', require: false
  gem 'timecop'
  gem 'webmock'
  gem 'vcr'
end

group :production do
  gem 'unicorn'
  gem 'rails_log_stdout', github: 'heroku/rails_log_stdout'
  gem 'rails3_serve_static_assets', github: 'heroku/rails3_serve_static_assets'
end
