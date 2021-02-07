# Bootstrap 4 - Kitchen Sink Page

## *Sample Page for **[Bootstrap 4.3.x](https://getbootstrap.com/)***

*Version 1.0*

## Why?
Great to for testing a build's custom styles against Bootstrap 4 components. Easily customize template for only the used elements.


## Setup Notes

This project requires ruby bundler, not a ruby dev.. I got you:

```
# Install rbenv
brew install rbenv

# Setup rbenv integration to your shell
rbenv init
rbenv install 2.6.3
rbenv global 2.6.3

# Install bundler
gem install --user-install bundler

# append your path with the gem dir
# eg in zsh: path=('/Users/mike/.gem/ruby/2.6.0/bin' $path)
# to get the path...
gem env

# install gems
bundle install

```

## Start Dev Server

```
bundler exec jekyll serve .
```

## Build Site ```./_site```

```
bundler exec jekyll build
```
