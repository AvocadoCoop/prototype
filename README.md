# Prototype

Figuring out collectively how to share and manage information

[Sourcing](https://github.com/AvocadoCoop/prototype/blob/main/sourcing.md)

## Static Site Generation
Using [Jekyll](https://jekyllrb.com/), because it plays the best with Github pages.

```sh
# Install ruby & gem first!
cd site_generator
# bundle is like npm. It will install the stuff from Gemfile.
bundle install
bundle exec jekyll s # Build and serve.
bundle exec jekyll clean # To remove generated files.
```