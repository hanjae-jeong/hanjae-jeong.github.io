source "https://rubygems.org"

gem "jekyll", ">= 4.0.0", "< 5.0"

# plugins
group :jekyll_plugins do
  gem "jekyll-paginate"
  gem "jekyll-redirect-from"
  gem "jekyll-seo-tag"
  gem "jekyll-archives"
  gem "jekyll-sitemap"
end

group :test do
  gem "html-proofer"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

gem "nokogiri", "~> 1.11"

gem "open-uri", "~> 0.1.0"

gem "ruby-readability", "~> 0.7.0"

gem "digest", "~> 3.0"
