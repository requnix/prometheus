# Prometheus

Prometheus is a utility library that helps you build graphical applications.
It is intended to simplify the process of constructing your application such
that your code reasons about behavior that is specific to your application
while addressing the need for lower level code to deal with rendering, input,
sound and other concerns in a (hopefully) cross-platform way.

I don't want to call it a "game engine" because it won't be complete enough to
be called that (at least for quite some time). However, if you want to start
writing an application in Crystal that is a game (or game-like) it may be of
use to you.

## Installation

Add this to your application's `shard.yml`:

```yaml
dependencies:
  prometheus:
    github: requnix/prometheus
```

## Usage

```crystal
require "prometheus"
```

TODO: Write usage instructions here

## Development

TODO: Write development instructions here

## Contributing

1. Fork it
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create a new Pull Request

## Contributors

- [[requnix]](https://github.com/requnix) Michael Prins - creator, maintainer
