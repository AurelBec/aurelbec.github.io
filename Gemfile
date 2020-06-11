source "https://rubygems.org"

gem "github-pages", "~> 228", group: :jekyll_plugins
gem "webrick", "~> 1.8.1"

## Theme
# gem "minima", "~> 2.5.1"

## Frontend framework
# gem "bootstrap"
# gem "jekyll-bootstrap-theme"

## Plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.15.1"
  gem "jekyll-tidy", "~> 0.2.2"
  gem "jekyll-sass-converter", "~> 1.5.2"
end

## Vulnerability fixes
#  see https://github.com/AurelBec/aurelbec.github.io/security/dependabot
# The kramdown gem before 2.3.0 for Ruby processes the template option inside Kramdown documents by default,
# which allows unintended read access (such as template="/etc/passwd") or unintended embedded Ruby code execution
# (such as a string that begins with template="string://<%= `).
# NOTE: kramdown is used in Jekyll, GitLab Pages, GitHub Pages, and Thredded Forum.
gem "kramdown", ">= 2.3.2"
gem "activesupport", ">= 6.1.7.1"
gem "addressable", ">= 2.8.0"
gem "commonmarker", ">= 0.23.7"
gem "nokogiri", ">= 1.13.6"
