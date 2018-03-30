# GORM (the fork with context support)

The fantastic ORM library for Golang, aims to be developer friendly.

[![go report card](https://goreportcard.com/badge/github.com/remohammadi/gorm "go report card")](https://goreportcard.com/report/github.com/remohammadi/gorm)
[![wercker status](https://app.wercker.com/status/ea43cc4e19d1e63076a9cd9fbc05f95d/s/master "wercker status")](https://app.wercker.com/project/byKey/ea43cc4e19d1e63076a9cd9fbc05f95d)
[![codecov](https://codecov.io/gh/jinzhu/gorm/branch/master/graph/badge.svg)](https://codecov.io/gh/jinzhu/gorm)
[![Join the chat at https://gitter.im/jinzhu/gorm](https://img.shields.io/gitter/room/jinzhu/gorm.svg)](https://gitter.im/jinzhu/gorm?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Open Collective Backer](https://opencollective.com/gorm/tiers/backer/badge.svg?label=backer&color=brightgreen "Open Collective Backer")](https://opencollective.com/gorm)
[![Open Collective Sponsor](https://opencollective.com/gorm/tiers/sponsor/badge.svg?label=sponsor&color=brightgreen "Open Collective Sponsor")](https://opencollective.com/gorm)
[![MIT license](https://img.shields.io/badge/license-MIT-brightgreen.svg)](https://opensource.org/licenses/MIT)
[![GoDoc](https://godoc.org/github.com/remohammadi/gorm?status.svg)](https://godoc.org/github.com/remohammadi/gorm)

## The Fork
This fork has an additional `WithContext` to utilize context support introduced in golang 1.8. I'm going to maintain this branch until gorm v2 is released.

## Overview

* Full-Featured ORM (almost)
* Associations (Has One, Has Many, Belongs To, Many To Many, Polymorphism)
* Hooks (Before/After Create/Save/Update/Delete/Find)
* Preloading (eager loading)
* Transactions
* Composite Primary Key
* SQL Builder
* Auto Migrations
* Logger
* Extendable, write Plugins based on GORM callbacks
* Every feature comes with tests
* Developer Friendly
* Supports context.Context on golang >=1.8

## Getting Started

* GORM Guides [https://gorm.io](https://gorm.io)

## Contributing

[You can help to deliver a better GORM, check out things you can do](https://gorm.io/contribute.html)

## License

© Jinzhu, 2013~time.Now

Released under the [MIT License](https://github.com/remohammadi/gorm/blob/master/License)
