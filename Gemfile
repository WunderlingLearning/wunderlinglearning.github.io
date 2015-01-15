# Skinny Bones Gemfile
source "https://rubygems.org"

gem 'jekyll', '~> 2.4.0'
gem 'jekyll-sitemap', '~> 0.6.1'
gem 'sass'
gem 'bourbon'
gem 'neat'
gem 'octopress', '~> 3.0.0.rc.12'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
