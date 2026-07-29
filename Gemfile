# frozen_string_literal: true

# Local development only. GitHub Pages builds this site server-side with its
# own pinned toolchain and ignores this file.

source 'https://rubygems.org'

gem 'jekyll', '~> 4.4'
gem 'jekyll-theme-minimal'

# jekyll-github-metadata is intentionally omitted: GitHub Pages injects it
# server-side, and locally it needs network access to the GitHub API. Without
# it, `site.github.*` is nil locally, so the "GitHub Profile" sidebar link only
# renders on the deployed site.
group :jekyll_plugins do
  gem 'jekyll-feed'
  gem 'jekyll-seo-tag'
end
