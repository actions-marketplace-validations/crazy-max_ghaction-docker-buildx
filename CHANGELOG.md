# Changelog

## 3.3.1 (2020/09/29)

* Action moved to Docker organization (#234)
* Update deps

## 3.3.0 (2020/08/17)

* Use crazy-max/ghaction-docker-login action
* Update deps

## 3.2.0 (2020/06/25)

* `qemu-version` not taken into account (#220)
* Remove `skip-cache` input

## 3.1.0 (2020/06/07)

* Handle nosuid (#213)

## 3.0.0 (2020/06/06)

* Use `actions/tool-cache` for caching
* `skip-cache` input no longer useful (deprecated)

## 2.0.1 (2020/06/03)

* Leverage buildx cache example
* Build and push to DockerHub example
* Update deps

## 2.0.0 (2020/05/29)

* Add cache implementation (#183)
* Remove `version` input.

## 1.6.2 (2020/05/20)

* Fix rename across "device" (partition) boundaries (#194)
* Update deps

## 1.6.1 (2020/05/08)

* Typo

## 1.6.0 (2020/05/07)

* Use native GitHub Action tools to download assets and use GitHub API
* Cleanup local paths from extra fields
* Remove `@actions/github` module and use `GITHUB_SHA` env var instead
* Audit packages

## 1.5.1 (2020/05/06)

* Add Codecov
* Update deps

## 1.5.0 (2020/04/30)

* Add `qemu-version` input
* Deprecate `version` input. Use `buildx-version` instead
* Use `actions/checkout@v2`
* Update deps

## 1.4.0 (2020/04/18)

* Support custom docker config home (#156)
* Update deps

## 1.3.0 (2020/04/09)

* Use ncc and clean workflows
* Update deps

## 1.2.1 (2020/03/29)

* Update deps

## 1.2.0 (2020/03/22)

* Use a unique name for the builder (#116)
* Update deps

## 1.1.0 (2020/03/19)

* Fix error on create (#114)
* Update deps

## 1.0.5 (2019/12/20)

* Update deps
* Fix lib

## 1.0.4 (2019/11/14)

* Update deps

## 1.0.3 (2019/10/09)

* Update release workflow

## 1.0.2 (2019/10/04)

* Update deps

## 1.0.1 (2019/10/04)

* Fix release workflow

## 1.0.0 (2019/10/04)

* Add tests
* Add release workflow

## 0.1.0 (2019/09/22)

* Initial version
