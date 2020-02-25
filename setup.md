---
title: Setup
layout: page
---

## Getting Started

This theme is based on [HPSTR Jekyll Theme](https://github.com/mmistakes/jekyll-theme-hpstr).
To learn how to install and use this theme check out the
[Setup Guide](https://mmistakes.github.io/jekyll-theme-hpstr/theme-setup/)
for more information.

Check also [Basic writing and formatting syntax](https://help.github.com/articles/basic-writing-and-formatting-syntax/)

### Ubuntu setup

Install [Jekyll](https://jekyllrb.com/docs/installation/ubuntu/)required dependencies

```console
sudo apt-get update
sudo apt-get install ruby-full build-essential zlib1g-dev
```

Set up a gem installation directory for your user account

```console
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

Install Bundler and and GitHub compatibile Jekyll and all dependencies

```console
gem install bundler github-pages
```

Navigate to this repository and install missing gems

```console
bundle install
```

Test your site

```console
bundle exec jekyll build
bundle exec jekyll serve --drafts
```

Browse to [http://localhost:4000](http://localhost:4000)
