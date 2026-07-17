# Jekyll 4 Gemfile. GitHub Actions builds the site with THIS file
# (.github/workflows/pages.yml); the original github-pages Gemfile is kept
# as Gemfile.github-pages for reference.
source "https://rubygems.org"

gem "jekyll", "~> 4.3"

# Pin Sass: newer Dart Sass errors on the theme's legacy SCSS (@import etc.);
# these versions only warn and build cleanly. Keeps local and CI identical.
gem "jekyll-sass-converter", "3.1.0"
gem "sass-embedded", "1.101.0"

group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-gist"
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-redirect-from"
  gem "jekyll-include-cache"
  gem "jemoji"
end

gem "webrick", "~> 1.9"

# stdlib gems extracted from default in recent Ruby releases
gem "csv"
gem "base64"
gem "bigdecimal"
gem "logger"
gem "ostruct"
