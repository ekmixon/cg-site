ruby '>= 2.5.7'

source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "~> 3.9", ">= 3.9.0"

# See https://github.com/envygeeks/jekyll-assets/issues/622
gem "sprockets", "~> 4.2", ">= 4.2.0"

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.13", ">= 0.13.0"
  gem 'jekyll-redirect-from'
  gem 'jekyll-paginate-v2', "2.0"
  gem 'jekyll-sitemap'
  gem 'jekyll-seo-tag'
  gem "jekyll-assets", "~> 3.0", ">= 3.0.12", group: :jekyll_plugins
  gem "jekyll-last-modified-at"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0" if Gem.win_platform?

gem "html-proofer", "~> 3.15", ">= 3.15.1"
gem "kramdown-parser-gfm"

gem "nokogiri", ">= 1.13.9"