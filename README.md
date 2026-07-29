# aahladmanas.github.io

Personal academic website for Aahlad Puli, built with Jekyll and hosted on GitHub Pages.

## Local development

Needs Ruby 3+ (macOS system Ruby 2.6 is too old — `brew install ruby`).

```sh
bundle install
bundle exec jekyll serve
```

If `eventmachine` fails to compile with `'iostream' file not found`, point it at
the SDK's C++ headers first:

```sh
SDK="$(xcrun --show-sdk-path)"
gem install eventmachine -v 1.2.7 -- \
  --with-cppflags="-isysroot $SDK -I$SDK/usr/include/c++/v1" \
  --with-cxxflags="-isysroot $SDK -std=c++11"
```

The local Gemfile is for development only — GitHub Pages builds the site
server-side with its own pinned toolchain and ignores it.

## Layout

- `index.md` — homepage: bio and news
- `publications.md` — publication list
- `talks.md` — invited talks and tutorials
- `notes.md` — notes index, rendered from `_posts/` (all posts currently `published: false`)
- `_layouts/default.html` — page shell and sidebar (CV link lives here)
- `assets/files/` — CVs
