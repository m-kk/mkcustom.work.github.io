# frozen_string_literal: true

source "https://rubygems.org"

gem "jekyll", "~> 4.3"
gem "jekyll-theme-chirpy", "~> 7.3", ">= 7.3.1"

gem "html-proofer", "~> 5.0", group: :test

group :jekyll_plugins do
  gem "jekyll-paginate"
  gem "jekyll-redirect-from"
  gem "jekyll-seo-tag"
  gem "jekyll-archives"
  gem "jekyll-sitemap"
  gem "jekyll-include-cache"
end

# Performance-booster for watching directories
gem "sassc", "~> 2.4"

platforms :windows, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:windows]
