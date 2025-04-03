source "https://rubygems.org"

# Use GitHub Pages gem which includes Jekyll and dependencies
gem "github-pages", group: :jekyll_plugins

# Specify platform for Windows users if needed
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Jekyll plugins
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-seo-tag"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
gem "webrick", "~> 1.7"
