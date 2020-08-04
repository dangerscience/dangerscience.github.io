source "https://rubygems.org"
ruby RUBY_VERSION

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "4.1.1"

# If you have any plugins, put them here!
group :jekyll_plugins do
   gem "jekyll-feed", "~> 0.13"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Capistrano
gem 'capistrano',         require: false
gem 'capistrano-chruby',  require: false
gem 'capistrano-bundler', require: false
gem 'ed25519', '~> 1.2'
gem 'bcrypt_pbkdf', '~> 1.0'
# Danger
gem 'danger'
gem 'danger-commit_lint'
gem 'danger-prose'
