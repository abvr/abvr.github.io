source "https://rubygems.org"

gem 'jekyll', '3.1.2' # this is the Jekyll version we are working with

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']