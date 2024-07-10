source "https://rubygems.org"

gem "jekyll", "~> 4.2.0"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-tidy"
  gem "jekyll-target-blank" # Add this line if you need this gem
end

gem "tzinfo", "~> 1.2", install_if: -> { RUBY_PLATFORM =~ /mingw|mswin|java/ }
gem "tzinfo-data", install_if: -> { RUBY_PLATFORM =~ /mingw|mswin|java/ }

gem "wdm", "~> 0.1.1", install_if: Gem.win_platform?

gem "jekyll-sitemap"
gem "kramdown-math-katex"

gem "webrick", "~> 1.7"
