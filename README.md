# go-tsz

* Package tsz implement time-series compression http://www.vldb.org/pvldb/vol8/p1816-teller.pdf in Go*

[![Master Branch](https://img.shields.io/badge/branch-master-lightgray.svg)](https://github.com/tsenart/go-tsz/tree/master)
[![Master Build Status](https://secure.travis-ci.org/tsenart/go-tsz.svg?branch=master)](https://travis-ci.org/tsenart/go-tsz?branch=master)
[![Master Coverage Status](https://coveralls.io/repos/tsenart/go-tsz/badge.svg?branch=master&service=github)](https://coveralls.io/github/tsenart/go-tsz?branch=master)
[![Go Report Card](https://goreportcard.com/badge/github.com/tsenart/go-tsz)](https://goreportcard.com/report/github.com/tsenart/go-tsz)
[![GoDoc](https://godoc.org/github.com/tsenart/go-tsz?status.svg)](http://godoc.org/github.com/tsenart/go-tsz)

## Description

Package tsz implement the  Gorilla Time Series Databasetime-series compression as described in:
http://www.vldb.org/pvldb/vol8/p1816-teller.pdf


## Getting started

This application is written in Go language, please refer to the guides in https://golang.org for getting started.

This project include a Makefile that allows you to test and build the project with simple commands.
To see all available options:
```bash
make help
```

## Running all tests

Before committing the code, please check if it passes all tests using
```bash
make qa
```
