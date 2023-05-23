---
hide_from_nav: true
---

# Technical Details
Using [Jekyll](https://jekyllrb.com/), because it plays the best with Github pages.

Sadly, it looks like to work with Github pages, a bunch of nonsense needs to be in the top level directory.

```sh
# Install ruby & gem first!
# bundle is like npm. It will install the stuff from Gemfile.
bundle install
bundle exec jekyll s # Build and serve.
bundle exec jekyll clean # To remove generated files.
```