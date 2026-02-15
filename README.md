# nm_chapter_blog


🚧 Please excuse the mess, construction in progress 🚧


# Local development

You'll need to install ruby, I recommend using asdf, then:

``` sh
gem install jekyll bundler
cd NM-SRA.github.io
bundle exec jekyll serve
```

and it should be available at http://127.0.0.1:4000/ in your browser

# Adding new blogs/deployment

Assuming you've got access to the repo, anytime you merge/push anything in to `main` in github it will kick off a fresh deployment.
It usually only takes a minute or two for your changes to be reflected in the live site at https://www.nm-sra.org/
