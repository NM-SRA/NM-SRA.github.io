# NM SRA Chapter Blog

🚧 Please excuse the mess, construction in progress 🚧

# Local development

You'll need to install ruby, I recommend using asdf, then:

``` sh
gem install jekyll bundler
cd NM-SRA.github.io
bundle exec jekyll serve
```

and it should be available at http://127.0.0.1:4000/ in your browser

# Adding new blog posts

To add new blog posts add a new file in the `_posts/_` directory. Makes sure the file name matches this pattern:

``` sh
2026-02-15-new-blog-post.jekyll.markdown
```

You'll also need to set up the header at the top of the file as such:

``` sh
---
layout: post
title:  "New blog post"
date:   2026-02-15 17:41:10 -0700
categories: cats dogs
---

This is the content of my new blog post.
```

Once you've finished, you'll need to push the changes to the repo which should kick off a deployment.

# Deployment

Assuming you've got access to the repo, anytime you merge/push anything in to `main` in github it will kick off a fresh deployment.
It usually only takes a minute or two for your changes to be reflected in the live site at https://www.nm-sra.org/

