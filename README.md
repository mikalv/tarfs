# TarFS

[![Build Status](https://travis-ci.org/posener/tarfs.svg?branch=master)](https://travis-ci.org/posener/tarfs)
[![codecov](https://codecov.io/gh/posener/tarfs/branch/master/graph/badge.svg)](https://codecov.io/gh/posener/tarfs)
[![GoDoc](https://godoc.org/github.com/posener/tarfs?status.svg)](http://godoc.org/github.com/posener/tarfs)
[![Go Report Card](https://goreportcard.com/badge/github.com/posener/tarfs)](https://goreportcard.com/report/github.com/posener/tarfs)

A wrapper around [`tar.Reader`](https://golang.org/pkg/archive/tar/#Reader).

  * Implements the [`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) for tar files.
  * Adds an `Open` method, that enables reading of file according to its' path.

## Get

`go get -u github.com/posener/tarfs`

## Example

See [the example](./examples/example_test.go).
