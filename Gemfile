source 'https://rubygems.org'
ruby '2.2.0'

### Back End Gems ###
gem 'hashids',  '1.0.2'     # Hashids is for bidirectional hashing
gem 'jbuilder', '2.0'       # https://github.com/rails/jbuilder
gem 'imgurapi'              # Imgur as image host
gem 'mini_magick', '4.2.9'  # Some magick imaging
gem 'rspotify'              # Spotify API gem
gem 'rack', '~> 1.6.4'
gem 'mysql2', '~> 0.3.18'   # Use mysql as databsae

### Middleware Gems ###
gem 'rails', '4.2.0'        # Bundle edge Rails instead
gem 'turbolinks'            # Turbolinks makes links in web app faster
gem 'httparty', '0.13.3'    # httparty for sending RESTful API requests

group :development, :test do
  gem 'better_errors'       # Way better exception screen for debugging
  gem 'byebug'              # Server debugger
  gem 'spring'              # Spring speeds up development
  gem 'awesome_print'       # Get some color into the console
end

group :production do
  gem 'puma'                # Use Puma over unicorn for concurrent requests
  gem 'pg'                  # Use mysql as database on heroku
  gem 'rails_12factor'      # So logs can work on heroku
end
