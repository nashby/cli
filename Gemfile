# frozen_string_literal: true

source "https://rubygems.org"
gemspec

unless ENV["CI"]
  gem "byebug", require: false, platforms: :mri
  gem "yard",   require: false
end

gem "dry-cli", "~> 0.6", require: false, git: "https://github.com/hanami/cli.git", branch: "feature/file-utils-class"

gem "hanami", require: false, git: "https://github.com/hanami/hanami.git", branch: "feature/hanami-2-cli"
