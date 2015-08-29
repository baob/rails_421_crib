# README

This is a repo with rails 4.2.2 generated, with a full set of testing
gems, compatible and configured.

## Setup

In the repo directory

    cp .ruby-gemset.example .ruby-gemset
    cp .ruby-version.example .ruby-version

Customise gemset as required

    cd .. ; cd - # establish the rvm config
    bundle install

## Tests

Run

    rake

which runs rspec and cucumber tests

