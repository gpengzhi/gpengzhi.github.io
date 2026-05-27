source "https://rubygems.org"

# NOTE: GitHub Pages does NOT use this Gemfile to build the site — it builds
# inside its own pinned container. So this Gemfile only affects local preview.
# We use Jekyll 4.x directly here because the legacy `github-pages` gem
# pins jekyll/liquid versions that no longer work on modern Ruby.

gem "jekyll", "~> 4.3"

gem "csv"
gem "bigdecimal"
gem "logger"

gem "wdm", "~> 0.1.0" if Gem.win_platform?

group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "jekyll-gist"
  gem "jekyll-redirect-from"
  gem "jekyll-paginate"
end
