source :rubygems

gemspec

group :development do
  gem "guard", "~> 0.8.8"
  if RUBY_PLATFORM.downcase.include?("darwin")
    gem "guard-rspec", "~> 0.5.4"
    gem "rb-fsevent", "~> 0.9"
    gem "growl", "~> 1.0.3"
  end
end
