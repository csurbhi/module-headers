# Change Log

All notable changes to this project will be documented in this file

# v0.0.13
## (2018-11-30)

# v0.0.20
## (2019-06-25)

* Fix target modpost not being built on kernel 5.0.3 [Florin Sarbu]

# v0.0.19
## (2019-06-22)

* Use native fixdep for target objtool on kernel 5.0.3 [Florin Sarbu]

# v0.0.18
## (2019-05-23)

* Pass LD when we run make for target [Zubair Lutfullah Kakakhel]

# v0.0.17
## (2019-05-23)

* Package module.lds for arm 64 bits [Florin Sarbu]

# v0.0.16
## (2019-05-17)

* Compile objtool fixdep binary for the target [Florin Sarbu]

# v0.0.15
## (2019-05-13)

* Use correct target for re-building the scripts [Florin Sarbu]

# v0.0.14
## (2019-02-21)

* Replicate sed command with context of 4.18 kernel [Sebastian Panceac]

* Fix changelog format for versionbot [Giovanni Garufi]

automatically by Versionist. DO NOT EDIT THIS FILE MANUALLY!
This project adheres to [Semantic Versioning](http://semver.org/).

# v0.0.12
## (2018-11-30)

* Add objtool support [Zubair Lutfullah Kakakhel]
* Pass separate native hostcc to modules_prepare [Zubair Lutfullah Kakakhel]

## v0.0.11

* Fix hostcc in module_prepare

## v0.0.10

* Fix aarch64 for kernel < 4.10

## v0.0.9

* Support kernel 4.13 which no longer has DocBook

## v0.0.8

* Fix build when vdso build is triggered

## v0.0.7

* Only copy directories if they exist.

## v0.0.6

* Add ability to cross-compile x86 to x86.

## v0.0.5

* Add parameter to allow use of custom cross-compiler when building `scripts/`
  binaries.

## v0.0.4

* Fix bug whereby if the `prefix` env var was set in the host it'd cause
  weirdness in the scripts/ bins dance.

## v0.0.3

* Updated script to correctly generate `scripts/` binaries for the _target_
  architecture.

## v0.0.2

* Transition to building without writing to the source directory.

## v0.0.1

First release.
