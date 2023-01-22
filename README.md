<!-- [![version](https://img.shields.io/badge/version-1.0.0-blue)](https://GitHub.com/Sollimann/CleanIt/releases/) -->
[![Build Status](https://github.com/Sollimann/msgpack-rpc/workflows/rust-ci/badge.svg)](https://github.com/Sollimann/msgpack-rpc/actions)
[![msgpack-rpc crate](https://img.shields.io/crates/v/msgpack-rpc.svg)](https://crates.io/crates/msgpack-rpc)
[![minimum rustc 1.56](https://img.shields.io/badge/rustc-1.56+-blue.svg)](https://rust-lang.github.io/rfcs/2495-min-rust-version.html)
[![Docs](https://docs.rs/msgpack-rpc/badge.svg)](https://docs.rs/msgpack-rpc)
[![codecov](https://codecov.io/gh/Sollimann/msgpack-rpc/branch/main/graph/badge.svg?token=JX8JBPWORV)](https://codecov.io/gh/Sollimann/msgpack-rpc)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Sollimann/msgpack-rpc/graphs/commit-activity)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/Sollimann/msgpack-rpc.svg)](https://GitHub.com/Sollimann/msgpack-rpc/pulls)
[![GitHub pull-requests closed](https://img.shields.io/github/issues-pr-closed/Sollimann/msgpack-rpc.svg)](https://GitHub.com/Sollimann/msgpack-rpc/pulls)
![ViewCount](https://views.whatilearened.today/views/github/Sollimann/msgpack-rpc.svg)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

msgpack-rpc
=======

A Rust implementation of MessagePack-RPC based on [tokio](http://tokio.rs/).

Features
========

- [X] Support all the features described in [MessagePack-RPC specifications](https://github.com/msgpack/msgpack/blob/master/spec.md).
- [X] Support for endpoints that act both as client and server. This is not part of the specification, but is a relatively common use of MessagePack-RPC.
- [X] Support any transport layer.

Examples
========

- [client.rs](https://github.com/little-dude/rmp-rpc/blob/master/examples/client.rs): a simple client
- [server.rs](https://github.com/little-dude/rmp-rpc/blob/master/examples/server.rs): a simple server
- [Ping Pong](https://github.com/little-dude/rmp-rpc/blob/master/examples/ping_pong.rs): an example with endpoints that are both client and server.
