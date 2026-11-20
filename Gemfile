source "https://rubygems.org"

# Match GitHub Pages’ dependency set for local builds.
# https://pages.github.com/versions/
# Note: github-pages >= 232 requires Ruby < 4.0 (see .ruby-version).
gem "github-pages", group: :jekyll_plugins
# Exact pin: github-pages requires 0.2.1.
gem "jekyll-include-cache", "0.2.1", group: :jekyll_plugins

# Needed for `bundle exec jekyll serve` on Ruby 3+
gem "webrick", "~> 1.7"

gem "tzinfo-data"
gem "wdm", "~> 0.1.0" if Gem.win_platform?
