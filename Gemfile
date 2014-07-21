source 'https://rubygems.org'

gem 'rails', '3.2.16'
gem 'jquery-rails'

group :development, :test do
     gem 'sqlite3'
end

group :production do
     gem 'pg'
     gem 'rails_12factor'
end

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
  gem 'bootstrap-sass', 
    git: 'https://github.com/twbs/bootstrap-sass', 
    ref: '540ad23430b1bdb2c72591daf61507ec9e38e468'
  gem 'bootstrap'
end