source "https://rubygems.org"
source "https://rails-assets.org"

gem "rails", "~> 4.2.0"
gem "rails-observers"

gem "coffee-rails", "~> 4.1.0" # Rails 4.2 default
gem "coffee-rails-source-maps", :group => :development
gem "jquery-rails"
gem "jquery-ui-rails"
gem "uglifier", ">= 1.3.0" # Rails 4.2 default

gem "sass-rails", "~> 5.0" # Rails 4.2 default

gem "rails-assets-jquery-cookie"
gem "rails-assets-mousetrap"

gem "non-stupid-digest-assets"

gem "pg", :platforms => [:ruby, :mingw]
gem "activerecord-jdbcpostgresql-adapter", "~> 1.3.0.rc1", :platforms => :jruby
gem "foreigner"

### FIXME: remove this
gem "actionpack-page_caching"
gem "protected_attributes"
### FIXME: remove this

gem "diff-lcs"
gem "json"
gem "dalli"
gem "connection_pool"
gem "acts_as_versioned_rails3"
gem "geoip"
gem "exception_notification"
gem "will_paginate"
gem "will-paginate-i18n"
gem "sitemap_generator"
gem "daemons", :require => false
gem "newrelic_rpm"
gem "nokogiri"
gem "rails-i18n"
gem "addressable", :require => "addressable/uri"
gem "mini_magick"
gem "image_size"
gem "cache_digests"
gem "i18n-js", ">= 3.0.0.rc7"

group :development do
  gem "quiet_assets"
end

group :standalone do
  platform :mri do
    gem "unicorn"
    gem "unicorn-worker-killer"
    gem "gctools"
  end
  gem "puma", :platforms => [:jruby, :rbx, :mswin]
end

gem "oj", :platforms => :mri
gem "multi_json"
gem "jbuilder", "~> 2.0" # Rails 4.2 default

# Must be last.
gem "rack-mini-profiler", :group => :development
