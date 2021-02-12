# Keep Gemfile.lock from repo. Reason: https://grosser.it/2015/08/14/check-in-your-gemfile-lock/

source 'https://rubygems.org'
git_source(:github)      { |repo| "git@github.com:#{repo}" }

platforms :jruby do
  gem 'jruby-openssl'
end

group :development, :test do
  gem 'pry'
end

gem "css_parser", github: 'kalilz4485/css_parser', branch: 'prevent-border-short-hand-kal'

gemspec
