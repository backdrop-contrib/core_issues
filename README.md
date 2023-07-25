## Core Issues Helper

This module includes submodules that can be enabled in demo sandboxes or local
environments, and then also on pull request sandboxes. Then you can compare the
output/behavior of the submodule in the current version of Backdrop core vs. the
pull request sandbox, and provide feedback on whether the problem for which the
respective issue was created for is fixed by the changes in the pull request or
not.

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
https://github.com/backdrop-contrib/mymodule/issues.


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
