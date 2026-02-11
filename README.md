## Archived 3rd-Party Fork

This repository is an archived copy of a 3rd-party open-source project that Progress Chef contributed to.

It was archived as part of the [Repository Standardization Initiative](https://github.com/chef-boneyard/oss-repo-standardization-2025).

No further contributions are anticipated to be made.

[![GitHub tag](https://img.shields.io/github/tag/xenolinguist/hoax.svg)]()
[![Build Status](https://secure.travis-ci.org/xenolinguist/hoax.png)](http://travis-ci.org/xenolinguist/hoax)
[![Hex.pm](https://img.shields.io/hexpm/v/hoax.svg)]()

  * [Build](#build)

hoax
====
Yet another mocking library for Erlang.

Build
-----

hoax requires [rebar][1] to build. To build hoax, go to the hoax
directory and simply type:

```sh
rebar compile
```

To make sure hoax works on your platform, run the tests:

```sh
rebar eunit
```

_Note that hoax's unit tests require Eunit >= 2.2.1 (OTP R14B04)._

  [1]: https://github.com/rebar/rebar "Rebar - A build tool for Erlang"
