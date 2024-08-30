source "https://rubygems.org"

# 주석 처리합니다
# gem "jekyll", "~> 4.3.3"

gem "minima", "~> 2.5"

# GitHub Pages gem을 주석 해제하고 활성화합니다
gem "github-pages", group: :jekyll_plugins

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-remote-theme"  # 이 줄을 추가합니다
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
