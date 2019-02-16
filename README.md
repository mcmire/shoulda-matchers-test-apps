# Shoulda Matchers test apps

This is a repo that holds fresh Rails apps useful for testing bugs in
[shoulda-matchers]. Most likely you were asked to come here by a maintainer of
the gem to reproduce a bug you were finding.

[shoulda-matchers]: http://github.com/thoughtbot/shoulda-matchers

The apps here correspond to the Rails versions and test frameworks that
shoulda-matchers officially supports. So far we have:

* [Rails 4.2.10 + RSpec](rails-4-2-and-rspec)
* [Rails 5.0.6 + RSpec](rails-5-0-and-rspec)
* [Rails 5.1.4 + RSpec](rails-5-1-and-rspec)
* [Rails 5.2.2 + RSpec](rails-5-2-and-rspec)

## Usage

Fork this repo and choose a Rails app. Each app comes pre-installed with
`rspec-rails` and `shoulda-matchers`, so you shouldn't need to set those up
(although you may have to point `shoulda-matchers` to the master branch, or
whatever version you are testing). No models or controllers exist, however —
feel free to add them as you see fit.

Once you've written tests to reproduce the bug you're finding, push up your
changes and post a link to your fork in the issue you came from (or if you're
done this before, [make a new issue]).

[make a new issue]: http://github.com/thoughtbot/shoulda-matchers/issues/new
