source "https://rubygems.org"

gem "jekyll", "3.5.2"
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

group :jekyll_plugins do
  gem 'jekyll-theme-slate', '~> 0.1.0'
  gem 'jekyll-feed'
end

group :ci do
  gem 'rake'
  gem 'html-proofer'
end
