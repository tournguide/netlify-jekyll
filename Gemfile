source "https://rubygems.org"

# Use GitHub Pages gem to ensure compatibility with GitHub Pages Jekyll version
gem "github-pages", group: :jekyll_plugins

# The default theme for Jekyll sites (optional, change if needed)
gem "minima", "~> 2.5"

# Optional plugins for additional features
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"  # RSS Feed plugin
  gem "jekyll-seo-tag", "~> 2.7"  # SEO metadata plugin
end

# Windows & JRuby specific gems for handling time zone data
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance booster for watching directories on Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` for JRuby builds
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
