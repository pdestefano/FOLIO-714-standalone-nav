This is the source for a FOLIO top navigation bar.

To contribute changes, please make the changes in a new branch and submit a
pull request.

Local development requires [curl](https://curl.haxx.se/) and
[Ruby](https://www.ruby-lang.org/) and [Bundler](https://bundler.io/).
The 'bundle install' step will install the relevant local
[Jekyll](https://jekyllrb.com/).

For Ruby, using [rbenv](https://github.com/rbenv/rbenv) and its 'ruby-build'
plugin ensures a smooth process. In this directory, set the ruby version
with: `rbenv local <version>`

Then do:

```
bundle install --path vendor/bundle
```

```
bundle exec jekyll serve --port 5000
```

```
bundle exec jekyll build
```

Occasionally do `bundle update` to advance the versions of dependencies.

