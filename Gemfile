# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }

# Specify your gem's dependencies in operator_recordable.gemspec
gemspec

gem "activerecord", ENV.fetch("AR_VERSION", "~> 5.2.3")
gem "request_store" unless ENV["WITHOUT_REQUEST_STORE"]
