# Buildkite Ruby rbenv Pipeline Example

[![Build status](https://badge.buildkite.com/aab023f2f33ab06766ed6236bc40caf0df1d9448e4f590d0ee.svg?branch=main)](https://buildkite.com/buildkite/ruby-rbenv-example)
[![Add to Buildkite](https://buildkite.com/button.svg)](https://buildkite.com/new)

This repository is an example on how to test a [Ruby](https://www.ruby-lang.org/en/) project using [Buildkite](https://buildkite.com/) and [rbenv](https://github.com/rbenv/rbenv). 

See the full [Getting Started Guide](https://buildkite.com/docs/guides/getting-started) for step-by-step instructions on how to get this running, or [Add to Buildkite](https://buildkite.com/new) to try it yourself.

<a href="https://buildkite.com/buildkite/ruby-rbenv-example/builds?branch=main"><img width="1491" alt="Screenshot of Buildkite ruby rbenv example pipeline" src=".buildkite/screenshot.png" /></a>
## How does it work?

It uses a local agent environment hook in [.buildkite/hooks/pre-command](.buildkite/hooks/pre-command) to setup rbenv.

See the [agent hook documentation](https://buildkite.com/docs/agent/hooks) for more information on how agent hooks work.

## License

See [Licence.md](Licence.md) (MIT)
