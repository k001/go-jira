# Changelog

## 0.0.5 - 2015-02-21

* handle editor having arguments [Cory Bennett] [[7186fb3](https://github.com/Netflix-Skunkworks/go-jira/commit/7186fb3)]
* add more template error handling [Cory Bennett] [[3e6f2b3](https://github.com/Netflix-Skunkworks/go-jira/commit/3e6f2b3)]
* allow create template to specify defalt watchers with -o watchers=... [Cory Bennett] [[4db2e4e](https://github.com/Netflix-Skunkworks/go-jira/commit/4db2e4e)]
* if config files are executable then run them and parse the output [Cory Bennett] [[7a2f7f5](https://github.com/Netflix-Skunkworks/go-jira/commit/7a2f7f5)]

## 0.0.4 - 2015-02-19

* add --template option to export-templates to export a single template [Cory Bennett] [[343fbb6](https://github.com/Netflix-Skunkworks/go-jira/commit/343fbb6)]
* add "table" template to be used with "list" command [Cory Bennett] [[8954ec1](https://github.com/Netflix-Skunkworks/go-jira/commit/8954ec1)]

## 0.0.3 - 2015-02-19

* [issue [#8](https://github.com/Netflix-Skunkworks/go-jira/issues/8)] detect X-Seraph-Loginreason: AUTHENTICATION_DENIED header to catch login failures [Cory Bennett] [[2dcf665](https://github.com/Netflix-Skunkworks/go-jira/commit/2dcf665)]
* project should always be uppercase [Jay Buffington] [[1b69d12](https://github.com/Netflix-Skunkworks/go-jira/commit/1b69d12)]
* if response is 400, check json for errorMessages and log them [Jay Buffington] [[4924dfa](https://github.com/Netflix-Skunkworks/go-jira/commit/4924dfa)]
* validate project [Jay Buffington] [[dc5ae42](https://github.com/Netflix-Skunkworks/go-jira/commit/dc5ae42)]

## 0.0.2 - 2015-02-18

* add missing --override options on transition command
* add browse command

## 0.0.1 - 2015-02-18

* Initial experimental release
