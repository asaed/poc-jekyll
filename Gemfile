# A sample Gemfile
source "https://rubygems.org"

# gem "rails"
require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json', {ssl_verify_mode: OpenSSL::SSL::VERIFY_NONE}).read)

gem 'github-pages', versions['github-pages']

