# mio-extras

Extra components for use with [Mio](https://github.com/tokio-rs/mio):

- a channel that implements `Evented`
- a timer that implements `Evented`

[![Crates.io][crates-badge]][crates-url]
[![Build Status][actions-badge]][actions-url]

[crates-badge]: https://img.shields.io/crates/v/mio-extras.svg
[crates-url]: https://crates.io/crates/mio-extras
[actions-badge]: https://github.com/dimbleby/mio-extras/actions/workflows/build.yml/badge.svg
[actions-url]: https://github.com/dimbleby/mio-extras/actions?query=workflow%3ACI+branch%3Amaster

[Documentation](https://docs.rs/mio-extras).

## History and maintenance

This repository is forked from
[`mio-more`](https://github.com/carllerche/mio-more), which is unmaintained.

This library is not compatible with mio 0.7.
However, there's a similar project named [`mio-misc`](https://github.com/onurzdg/mio-misc) that works with mio 0.7.

I don't intend to do very much with this except for routine maintenance - bug
fixes, updating dependencies, and suchlike.

However if you have some code that you think belongs here, then by all means
raise an issue or open a pull request.

# License

`mio-extras` is primarily distributed under the terms of both the MIT license
and the Apache License (Version 2.0), with portions covered by various BSD-like
licenses.

See LICENSE-APACHE, and LICENSE-MIT for details.
