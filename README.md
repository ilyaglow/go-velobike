# go-velobike

[![GoDoc](https://godoc.org/github.com/rumyantseva/go-velobike/velobike?status.svg)](https://godoc.org/github.com/rumyantseva/go-velobike/velobike)
[![Go Report Card](https://goreportcard.com/badge/github.com/rumyantseva/go-velobike)](https://goreportcard.com/report/github.com/rumyantseva/go-velobike)
[![Build Status](https://travis-ci.org/rumyantseva/go-velobike.svg?branch=master)](https://travis-ci.org/rumyantseva/go-velobike)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/rumyantseva/go-velobike/issues)

This is an unofficial Go client library to deal with REST API of velobike.ru project

Client style based on the best practices of [google/go-github](https://github.com/google/go-github).

## Versioning

Semantic versioning: Major.Minor.Patch.
Current version is v3.x.x.

If you use this library, please vendor it using a package management tool to not to have backward compatibility problems in the future.

If you have any questions, feel free to [create an issue](https://github.com/rumyantseva/go-velobike/issues/new), I'll try to answer as soon as possible.

## Supported methods

* GET /profile
* POST /profile/authorize
* GET /ride/parkings
* GET /ride/history

## Contributing

Contributors are welcome! Feel free to improve this project or share your ideas via [issues](https://github.com/rumyantseva/go-velobike/issues).

Contributors (unsorted):

* Elena Grahovac: [@rumyantseva](https://github.com/rumyantseva)
* Pavel Borzenkov: [@pborzenkov](https://github.com/pborzenkov)
* Bill Glover: [@billglover](https://github.com/billglover)
* [jainnidhi703](https://github.com/jainnidhi703)
* [gunjan01](https://github.com/gunjan01)

## Roadmap

* Add electric bikes
* Add GET /content/news method
