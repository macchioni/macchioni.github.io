source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'jekyll', '3.3.1'

group :jekyll_plugins do
	gem "jekyll-sitemap"
	gem "jekyll-seo-tag"
end