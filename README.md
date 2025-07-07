# Buildkite Ruby rbenv Example

[![Build status](https://badge.buildkite.com/aab023f2f33ab06766ed6236bc40caf0df1d9448e4f590d0ee.svg?branch=main)](https://buildkite.com/buildkite/ruby-rbenv-example/builds/latest?branch=main)
[![Add to Buildkite](https://img.shields.io/badge/Add%20to%20Buildkite-14CC80)](https://buildkite.com/new)

This repository is an example [Buildkite](https://buildkite.com/) pipeline that demonstrates how to test a [Ruby](https://www.ruby-lang.org/en/) project using [rbenv](https://github.com/rbenv/rbenv).

👉 **See this example in action:** [buildkite/ruby-rbenv-example](https://buildkite.com/buildkite/ruby-rbenv-example/builds/latest?branch=main)

See the full [Getting Started Guide](https://buildkite.com/docs/guides/getting-started) for step-by-step instructions on how to get this running, or try it yourself:

[![Add to Buildkite](https://buildkite.com/button.svg)](https://buildkite.com/new)

<a href="https://buildkite.com/buildkite/ruby-rbenv-example/builds/latest?branch=main">
  <img width="2400" alt="Screenshot of example pipeline build page" src=".buildkite/screenshot.png" />
</a>

<!-- docs:start -->
## How it works

This example:
- Uses a [pre-command hook](.buildkite/hooks/pre-command) to load `rbenv`
- Runs Ruby tests using the version specified in `.ruby-version`

Key files:
- [`pre-command`](.buildkite/hooks/pre-command) – loads `rbenv` before each job runs
- [`pipeline.yml`](.buildkite/pipeline.yml) – defines the pipeline steps

See the [Agent hook documentation](https://buildkite.com/docs/agent/hooks) for more information about Buildkite’s agent hooks.

<!-- docs:end -->

## License

See [LICENSE.md](LICENSE.md) (MIT)
