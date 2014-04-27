## www.atlang.org

This repository contains the _static_ source of the atlang website.

## Dependencies

You'll need Jekyll installed to generate and test the site. To get it, most people can install via RubyGems:

    gem install jekyll

OSX users might have to update RubyGems:

    sudo gem update --system

If in doubt, head over to the [Jekyll wiki](https://github.com/mojombo/jekyll/wiki) for installation instructions.

## Building

After cloning, cd into the `atlang/www.atlang.org` directory and run:

    jekyll serve

To see the generated site, just visit `http://localhost:4000`.

To have the site regenerated as you make changes, use the `--watch` flag:

    jekyll serve --watch