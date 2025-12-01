# Zhen's Website

## How to Run Locally

If Bundler itself isn't fully set up, install/update it globally:
```bash
gem install bundler
```

Then, in your site directory, install the project's gems (this pulls in Jekyll and dependencies from the Gemfile):
```bash
bundle install
```

Now use bundle exec to run it in the bundled environment:
```bash
bundle exec jekyll serve
```
This should start the local server at http://127.0.0.1:4000 (or http://localhost:4000).

If Ruby is outdated, install ruby on macOS:
```bash
brew install ruby
```
Then reinstall gems: `gem install bundler` and `bundle install`.