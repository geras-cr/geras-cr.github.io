source "https://rubygems.org"

# Ruby 3.4+ removed these from the default gems; github-pages/jekyll still need them.
gem "bigdecimal"
gem "logger"
gem "csv"
gem "base64"

gem "github-pages", group: :jekyll_plugins

group :jekyll_plugins do
  gem "jekyll-sitemap"
  gem "jekyll-feed"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "wdm", "~> 0.1.1"
end
