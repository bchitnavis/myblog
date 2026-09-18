source "https://rubygems.org"

# GitHub Pages-compatible Jekyll setup
gem "github-pages", group: :jekyll_plugins
gem "webrick", "~> 1.8"

# Keep these only if you want local plugin support beyond GitHub Pages defaults
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-include-cache"
  gem "jekyll-seo-tag"
  gem "jekyll-paginate"
  gem "jekyll-archives"
end

# Windows and JRuby support
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", platforms: [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]
