# ![](https://fonts.gstatic.com/s/i/materialiconsoutlined/flare/v4/24px.svg) Service
[![](https://img.shields.io/github/v/release/codemodify/systemkit-service-tests?style=flat-square)](https://github.com/codemodify/systemkit-service-tests/releases/latest)
![](https://img.shields.io/github/languages/code-size/codemodify/systemkit-service-tests?style=flat-square)
![](https://img.shields.io/github/last-commit/codemodify/systemkit-service-tests?style=flat-square)
[![](https://img.shields.io/badge/license-0--license-brightgreen?style=flat-square)](https://github.com/codemodify/TheFreeLicense)

![](https://img.shields.io/github/workflow/status/codemodify/systemkit-service-tests/qa?style=flat-square)
![](https://img.shields.io/github/issues/codemodify/systemkit-service-tests?style=flat-square)
[![](https://goreportcard.com/badge/github.com/codemodify/systemkit-service-tests?style=flat-square)](https://goreportcard.com/report/github.com/codemodify/systemkit-service-tests)

[![](https://img.shields.io/badge/godoc-reference-brightgreen?style=flat-square)](https://godoc.org/github.com/codemodify/systemkit-service-tests)
![](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)
![](https://img.shields.io/gitter/room/codemodify/systemkit-service-tests?style=flat-square)

![](https://img.shields.io/github/contributors/codemodify/systemkit-service-tests?style=flat-square)
![](https://img.shields.io/github/stars/codemodify/systemkit-service-tests?style=flat-square)
![](https://img.shields.io/github/watchers/codemodify/systemkit-service-tests?style=flat-square)
![](https://img.shields.io/github/forks/codemodify/systemkit-service-tests?style=flat-square)


# ![](https://fonts.gstatic.com/s/i/materialicons/extension/v5/24px.svg) What
>Robust cross platform _`CREATE`_ / _`DELETE`_ / _`START`_ / _`STOP`_ / _`QUERY`_ system service in Command Line an from scripts
>
> _This repo is a cross platform CLI reference implementation of the [<u>__SERVICE__</u>](https://github.com/codemodify/systemkit-service-spec) spec_

- automatically from scripts
- format conversion from one format to another

# ![](https://fonts.gstatic.com/s/i/materialicons/build/v5/24px.svg) How
>```sh
>systemkit-service-tests-cli create -name test-service -executable vim
>systemkit-service-tests-cli delete -name test-service
>systemkit-service-tests-cli start -name test-service
>systemkit-service-tests-cli stop -name test-service
>systemkit-service-tests-cli info -name test-service
>systemkit-service-tests-cli convert -to SERVICE -from rc_d -file FILE
>```
