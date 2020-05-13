#since war/jar bundle requires gem package; use gem-in-a-box for testing
#or execute tabula via "rackup".
#source "http://127.0.0.1:9292"

source "https://rubygems.org"
platform :jruby do
  gem "cuba", ">= 3.8.0"
  gem "rack", "~> 2.1.3"
  gem "tilt", "~> 1.4.0"

  group :development do
    gem "rake"
    gem "warbler", "~> 1.4.9"
    gem "jruby-jars", "1.7.24"
    gem "bootstrap-sass", "~> 3.2.0"
    gem "compass"
  end
end
