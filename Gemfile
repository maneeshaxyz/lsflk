source "https://rubygems.org"

# Use the latest stable version of Jekyll
gem "jekyll", "~> 4.3"

# Required for the 'jekyll serve' command in Jekyll 4+
gem "webrick"

# Add all plugins your site uses
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
end

# Add all gems that Ruby 3.4 now requires you to list explicitly
gem "csv"
gem "base64"
gem "bigdecimal"
gem "logger"
gem "fiddle"

# Windows-specific gems for development
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
  gem "wdm", "~> 0.1"
end