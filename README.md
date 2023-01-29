# Overview

This is a simple Github Pages website I threw together based on [minimal](https://github.com/pages-themes/minimal).

[![.github/workflows/ci.yaml](https://github.com/finbarrtimbers/hire-us/actions/workflows/ci.yaml/badge.svg)](https://github.com/pages-themes/minimal/actions/workflows/ci.yaml) 


## Previewing the site locally

If you'd like to preview the theme locally (for example, in the process of proposing a change):

1. Clone down the theme's repository (`git clone https://github.com/pages-themes/minimal`)
2. `cd` into the theme's directory
3. Run `script/bootstrap` to install the necessary dependencies
4. Run `bundle exec jekyll serve` to start the preview server
5. Visit [`localhost:4000`](http://localhost:4000) in your browser to preview the theme

## Running tests

The theme contains a minimal test suite, to ensure a site with the theme would build successfully. To run the tests, simply run `script/cibuild`. You'll need to run `script/bootstrap` once before the test script will work.
