source 'http://rubygems.org'

gem "rails", "3.0.3"
gem "mysql2"
gem "haml"
gem "delayed_job"
gem "stringex"
gem "open4"
gem "json"

# ruby 1.9 compatible version
gem "scashin133-xmpp4r-simple", '0.8.9', :require => 'xmpp4r-simple'

# irc notification
gem "shout-bot"

# campfire notifications
gem "tinder"

group :development, :test do
  gem "sqlite3-ruby"
  gem "capybara"
  gem "launchy"
  gem "faker"
  gem "machinist"
  gem "nokogiri"
  gem "mocha"
  gem "database_cleaner"
  gem "crack"

  platforms :mri_18 do
    gem "ruby-debug"
  end

  platforms :mri_19 do
    gem "ruby-debug19"
  end
end
