
   source "https://rubygems.org"

   # Use github-pages for GitHub Pages compatibility
   gem "github-pages", "~> 231", group: :jekyll_plugins

   # Add csv gem for Ruby 3.4.0 compatibility
   gem "csv", "~> 3.2"

   # Add webrick for local Jekyll server
   gem "webrick", "~> 1.8"

   # Add fiddle to silence Ruby 3.5.0 warning
   gem "fiddle", "~> 1.1"

   # Jekyll plugins
   group :jekyll_plugins do
     gem "jekyll-feed", "~> 0.12"
     gem "jekyll-seo-tag", "~> 2.8"
   end

   # Windows and JRuby specific gems
   platforms :mingw, :x64_mingw, :mswin, :jruby do
     gem "tzinfo", ">= 1", "< 3"
     gem "tzinfo-data"
   end

   # Performance-booster for watching directories on Windows
   gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

   # Lock http_parser.rb for JRuby
   gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]