source "https://rubygems.org"
ruby RUBY_VERSION

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "4.3.1"

# This is the default theme for new Jekyll sites. You may change this to anything you like.
#gem "minima", "~> 2.0"
#gem "minimal-mistakes-jekyll"

# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "minima", "~> 2.5"
#gem "jekyll-theme-leap-day"
gem "jekyll-theme-cayman", "~> 0.2.0"
gem "jekyll-theme-yat"
#gem "minimal-mistakes-jekyll"

# If you have any plugins, put them here!
group :jekyll_plugins do
   gem "jekyll-remote-theme"
   gem "jekyll-seo-tag"
   gem "jekyll-feed", "~> 0.6"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
