source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'jekyll', '3.3.1'

group :jekyll_plugins do
	gem 'github-pages', versions['github-pages']
	gem 'jekyll-seo-tag'
	gem 'jemoji'
	gem 'jekyll-sitemap'
end