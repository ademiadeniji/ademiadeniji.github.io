source 'https://rubygems.org'
ruby '3.2.8'

group :jekyll_plugins do
    gem 'classifier-reborn'
    gem 'jekyll', '~> 4.3.4'
    gem 'jekyll-archives', '~> 2.2.1'
    gem 'jekyll-email-protect', '~> 1.1.0'
    gem 'jekyll-feed', '~> 0.17.0'
    gem 'jekyll-get-json', '~> 0.0.1'
    gem 'jekyll-imagemagick', '~> 1.4.0'
    gem 'jekyll-jupyter-notebook'
    gem 'jekyll-link-attributes', '~> 0.0.1'
    gem 'jekyll-minifier', '~> 0.1.10'
    gem 'jekyll-paginate-v2', '~> 3.0.0'
    gem 'jekyll-regex-replace', '~> 1.1.0'
    gem 'jekyll-scholar', '~> 7.1.3'
    gem 'jekyll-sitemap', '~> 1.4.0'
    gem 'jekyll-tabs', '~> 1.0.0'
    gem 'jekyll-toc', '~> 0.18.0'
    gem 'jemoji', '~> 0.13.0'
    gem 'unicode_utils', '~> 1.4.0'
    gem 'webrick', '~> 1.8.1'
    gem 'faraday-retry', '~> 2.2'
end
group :other_plugins do
    gem 'css_parser', '~> 1.12.0'
    gem 'feedjira', '~> 3.2.0'
    gem 'httparty', '~> 0.21.0'
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
