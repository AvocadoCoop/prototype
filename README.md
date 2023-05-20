---
layout: page
title: Sourcing Products
last_verified: 2023-05-18
---

# Prototype

Figuring out collectively how to share and manage information

[Sourcing](https://github.com/AvocadoCoop/prototype/blob/main/sourcing.md)

## Static Site Generation
Using [Jekyll](https://jekyllrb.com/), because it plays the best with Github pages.

```sh
# Install ruby & gem first!
gem install jekyll
cd site_generator
# Make sure ruby gems is on your path.
jekyll b # To build once.
jekyll s # To serve with live updates.
jekyll clean # To remove generated files.
```