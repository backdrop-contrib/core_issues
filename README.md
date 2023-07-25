## Core Issues Helper

This module is meant to make it easier for people to contribute to core issues.
It provides various submodules, each one specific to different issue(s).

The process roughly looks like this:

- The person that has provided a pull request for a core issue can contribute to
  this project here, by creating a new submodule. (todo: add instructions for
  that + also a template submodule scaffold)
- The submodule is then reviewed/approved by the maintainers of this here
  project (anyone can join to help out - even the person that is submitting the
  submodule for review), and a new release for the Core Issue Helper module is
  created.
- People that want to contribute by testing pull requests can then:
  - Install the Core Issue Helper module either in a [demo sandbox](https://backdropcms.org/demo)
    or on their local environment.
  - Enable the submodule that corresponds to the issue they are contributing to.
  - Also install the module and submodule(s) on the sandbox of the pull request
    of the issue they are contributing to.
  - Compare the output/behavior of the submodule in the current version of
    Backdrop core vs. the version in the pull request sandbox (which includes
    the changes that are meant to be fixing the issue).
  - Provide feedback on whether they have found the problem for which the
    respective issue was created for to be fixed by the changes in the pull
    request or not.
  - Gain the eternal gratitude of everyone in the Backdrop community! ❤️

Each submodule is named `issue_1234`, where `1234` is the issue number of the
[core issue](https://github.com/backdrop/backdrop-issues/issues) the module is
meant to help testing.

### Requirements
---

None specific, but depending on the core issue some submodules may have
dependencies on other modules.

### Installation
---

- Install this module using the official Backdrop CMS instructions at
  https://docs.backdropcms.org/documentation/extend-with-modules.
- Navigate to the module management page, and enable the submodule(s) you need
  in order to test the issue(s) you are contributing to.
- Once enabled, each module should have a "Configure" link available, that when
  clicked takes you to a page with further instructions and/or a test form etc.
- Follow the instructions provided on the module page, or in the issue you are
  contributing to.
- Report back with the findings of your testing.

### Documentation
---

Additional documentation is located in the Wiki:
https://github.com/backdrop-contrib/core_issues/wiki/Documentation (todo)


### Issues
---

Bugs and Feature Requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/core_issues/issues

### Current Maintainers
---

- [Greg Netsas](https://github.com/klonos)
- Seeking additional maintainers (either create an issue in the queue, or
  @mention one of the current maintainers in our [chat](https://backdrop.zulipchat.com/#narrow/stream/218635-Backdrop/topic/Core.20Issues.20Helper)).

### Credits
---

- Originally written for Backdrop by [Greg Netsas](https://github.com/klonos).

### License
---

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.
