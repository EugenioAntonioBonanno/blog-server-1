# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem "roda"
gem "puma"

gem "sequel"
gem "sqlite3"

gem "slim"
gem "pry"

# gem "oj"
# gem "http"

group :development do
  gem "shotgun"
end

group :development, :test do
  gem "dotenv"
  gem "warning"
end

group :test do
  gem "minitest"
  gem "minitest-hooks"
end
