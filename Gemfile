source "https://rubygems.org"

# Core gem for GitHub Pages support (includes Jekyll and many plugins)
gem "github-pages", group: :jekyll_plugins

# ✅ Windows-specific time zone support (already included here for good measure)
# gem "tzinfo-data"

# ⚠️ Optional: Uncomment if you want file watching on Windows (causes build issues on newer Ruby versions)
# gem "wdm", "~> 0.1.0" if Gem.win_platform?

# 💡 You can add general-purpose gems here (outside the :jekyll_plugins group)

# Plugins and theme helpers
group :jekyll_plugins do
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-gist"
  gem "jekyll-feed"
  gem "jemoji"
  gem "jekyll-include-cache"
  gem "jekyll-algolia"
  gem "tzinfo-data"
  gem "jekyll-seo-tag"

  # ✅ Required for Ruby 3.4+ and to prevent 'uninitialized constant TZInfo::Timezone' errors
  gem "tzinfo", "~> 2.0"

  # ✅ Silences Ruby 3.5+ deprecation warnings for Windows users
  gem "fiddle"
  gem "ostruct"

  # ✅ Adds retry middleware for Faraday (used by jekyll-algolia and others)
  gem "faraday-retry"
end