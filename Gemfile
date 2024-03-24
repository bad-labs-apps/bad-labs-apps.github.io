source "https://rubygems.org"

gem "jekyll"
gem "minima"
gem "kramdown-parser-gfm"
gem "webrick"
gem "wdm", :install_if => Gem.win_platform?

group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-last-modified-at"
end

install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo"
  gem "tzinfo-data"
end
