# frozen_string_literal: true

source "https://rubygems.org"

gem "hanami", "~> 2.0.0.rc"
gem "hanami-router", "~> 2.0.0.rc"
gem "hanami-controller", "~> 2.0.0.rc"
gem "hanami-validations", "~> 2.0.0.rc"

gem "dry-types", "~> 1.0", ">= 1.6.1"
gem "puma"
gem "rake"

group :development, :test do
  gem "dotenv"
end

group :cli, :development do
  gem "hanami-reloader"
end

group :cli, :development, :test do
  gem "hanami-rspec"
end

group :development do
  gem "guard-puma"
end


group :test do
  gem "rack-test"
end

gem "alba", path: "~/Code/alba"
# gem "alba", github: "trevorturk/alba", branch: "automatic-inflector"
