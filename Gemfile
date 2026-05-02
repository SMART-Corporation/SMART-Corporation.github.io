source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "4.4.0"

# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "minima", "~> 2.5"

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins

# If you have any plugins, put them here!
group :jekyll_plugins do
   gem "jekyll-feed", "~> 0.12"
   gem 'jekyll-gist'
   gem 'jekyll-paginate'
   gem "jekyll-asciidoc"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
   gem "tzinfo", "~> 1.2"
   gem "tzinfo-data"
end
 
# wdm removed: abandoned gem, incompatible with Ruby 3.3+
 
# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

gem "webrick", "~> 1.7"


# Template specific
gem 'asciidoctor', '~> 1.5.4'
gem 'coderay', '1.1.1'

# HTTP/REST API client library
gem 'faraday', '~> 2.5', '>= 2.5.2'
gem 'faraday-retry', '~> 2.0'
