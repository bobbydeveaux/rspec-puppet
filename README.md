RSpec Ruby Tests
==============

Repo to show how to test puppet scripts with RSpec

Getting started
----------

Head over to your modules dir (cd path/to/modules)

    puppet module generate bobby-logrotate

    rspec-puppet-init

    bundle install

    bundle exec rake spec

Your code coverage will be in the coverage folder.

Happy testing!
