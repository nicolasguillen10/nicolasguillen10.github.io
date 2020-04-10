nicolasguillen.ch
===============

Portfolio site


Development
===========

Ensure you have the correct version of Ruby installed (per `.ruby-version`). Also ensure you have the Bundler gem installed.


One-time setup
--------------

    bundle install --path vendor/bundle

_Note: If you're on Mac OS and this fails installing nokogiri, run `brew unlink xz`, install, and then `brew link xz`._

Running the site
----------------

Local development:

    bundle exec jekyll serve
