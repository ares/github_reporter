# Installation

To install the application dependencies, use bundler.

# Usage

Create a configuration in a new file config.yaml, you can take a look
at config.yaml.example for inspiration (it's a working config file).
Then run

```
bundle exec ruby github_reporter.rb
```

it should print tables with open pull requests on configured github
repositories for specified users. Make sure your working directory
is the root of this app.

# Tests

To run test just use rake test task like this

```
bundle exec rake test
```
