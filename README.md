semver
======

Semantic version parsing and comparison. Fork of [the `semver` crate][semver-crate] which adds support for parsing of versions outside of [the semver spec][semver-spec], but popular in the wild. See [issue 219](https://github.com/steveklabnik/semver/issues/219).

Namely we extend [the parent crate][semver-crate] to support:

```
"x.y" => "x.y.0"
"x" => "x.0.0"
```

For more information about every other aspect see the parent crate.

## Installation

To use `forgiving_semver`, add this to your `[dependencies]` section:

```toml
forgiving_semver = "0.11.0"
```

<!-- References -->
[semver-spec]: https://semver.org
[semver-crate]: https://steveklabnik.github.io/semver
