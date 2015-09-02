# Rails in one hour

## Setup

```bash
$ bundle
$ rake newb
```

## Definition of Done

In addition to satisfying acceptance criteria, new functionality/changes/etc
must meet the following requirements before they can be considered "done":

1. Be well-tested according to our
   [Automated Testing Policy](#automated-testing-policy), and the test suite
   must be passing.
1. [Conform to the Ruby Community Styleguide.](#styleguide-enforcement)
1. Update the seed file with any new data that QA will need to accept your feature
1. Ensure that any new ENV vars are added to `setup.rb` and updated on CI and
   servers
1. Views render correctly in all [supported browsers](#supported-browsers)
1. Have received the :shipit: in peer review via Pull Request.

## Automated Testing Policy

TODO: Add your team's agreed upon policy here.

## Styleguide Enforcement

We run [rubocop][rubocop] with near vanilla configs to enforce the Ruby Community
Styleguide. It runs as part of the default `$ rake` task on CI or can be run on
its own with `$ rubocop`.

[rubocop]: https://github.com/bbatsov/rubocop

## Browser Compatibility

TODO: Add your team's agreed upon policy here.
