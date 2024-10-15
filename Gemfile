source "https://rubygems.org"

ruby "3.3.5"

# Bundle edge Rails instead:
gem "rails", github: "rails/rails", branch: "main"
# gem "rails", "~> 7.2"

# Panda CMS
gem "panda_cms", github: "pandacms/panda_cms", branch: "main"

# The modern asset pipeline for Rails [https://github.com/rails/propshaft]
gem "propshaft"

# Kamal for deployments
gem "kamal"

# Use postgresql as the database for Active Record
gem "pg", "~> 1.1"

# Use the Puma web server [https://github.com/puma/puma]
gem "puma", ">= 5.0"

# Use JavaScript with ESM import maps [https://github.com/rails/importmap-rails]
gem "importmap-rails"

# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem "turbo-rails"

# Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem "stimulus-rails"

# Use Tailwind CSS [https://github.com/rails/tailwindcss-rails]
gem "tailwindcss-rails"

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem "jbuilder"

# Solid queue
gem "solid_queue"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

# Sentry for error reporting
gem "stackprof"
gem "sentry-ruby"
gem "sentry-rails"

gem "lograge", "~> 0.14.0"

gem "concurrent-ruby", "~> 1.3.4"
gem "concurrent-ruby-ext", "~> 1.3.4"

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[mri windows]

  gem "annotate", ">= 3.2.0"
  gem "erb_lint" # , require: false
  gem "letter_opener_web", "~> 3.0"
  gem "rspec-rails", "~> 6.0"
  gem "rspec-retry"
  gem "standard"

  # Security tooling
  gem "brakeman"
  gem "bundler-audit"

  # Bullet checks for N+1s
  # gem "bullet"

  # Suggest Ruby speed improvements
  gem "fasterer"

  # Suggest Ruby style improvements
  gem "reek"

  # Ruby-LSP
  gem "ruby-lsp"

  # Yard for documentation
  gem "yard-activerecord"
end

group :development do
  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  gem "spring"

  # Add schema_to_scaffold for generating scaffolds from schema.rb
  gem "schema_to_scaffold"

  # Add rubycritic for code quality
  gem "rubycritic", require: false

  # Add better_errors for improved error pages
  gem "better_errors"
  gem "binding_of_caller"
end

group :test do
  gem "capybara"
  gem "capybara-screenshot"
  gem "cucumber-rails", require: false
  gem "cuke_linter"
  gem "database_cleaner"
  gem "email_spec"
  gem "factory_bot_rails"
  gem "factory_trace"
  gem "faker"
  gem "selenium-webdriver", ">= 4.11.0"
  gem "shoulda-matchers"
  gem "simplecov", require: false
  gem "simplecov-json", require: false
  gem "webmock"
end
