Personal Website of Ye Yuan.

Template forked from [academic websites](https://github.com/academicpages/academicpages.github.io), originally forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), which is © 2016 Michael Rose and released under the MIT License. See LICENSE.md.

## To run locally
1. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
1. Run `bundle clean` to clean up the directory (no need to run `--force`)
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `bundle exec jekyll liveserve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.
1. Delete the Gemfile.lock file to handle security vulnerability notification.

## Changelog

1. `_config.yml`
1. `data/navigation.yml`
1. `_include/archive-single.html`
1. `_layouts`
