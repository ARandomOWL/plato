# Concepts

[![Build Status](https://travis-ci.org/tuura/plato.svg?branch=master)](https://travis-ci.org/tuura/plato)
[![Build status](https://ci.appveyor.com/api/projects/status/eyfuyi0v9v1ulcgn?svg=true)](https://ci.appveyor.com/project/jrbeaumont/plato-9uatd)

A DSL for asynchronous circuits specification.

### Requirements

To build and run the translation tool, Stack is needed, and can be downloaded for all operating systems from
<https://docs.haskellstack.org/en/stable/install_and_upgrade/>

### Build

	stack setup --no-system-ghc
	stack build

### Test

	stack test

### Translate to STG

Invoke the translate executable with a concept circuit file:

	stack runghc translate/Main.hs examples/celement_with_env_1.hs

### Manual

The manual can be found at [doc/manual.md](https://github.com/tuura/concepts/blob/master/doc/manual.md)
