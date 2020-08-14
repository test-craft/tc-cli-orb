## TestCraft cli Orb 
[![CircleCI Build Status](https://circleci.com/gh/test-craft/tc-cli-orb/tree/master.svg?style=shield "CircleCI Build Status")](https://app.circleci.com/pipelines/github/test-craft/tc-cli-orb) [![CircleCI Orb Version](https://img.shields.io/badge/endpoint.svg?url=https://badges.circleci.io/orb/circleci/gradle)](https://circleci.com/orbs/registry/orb/testcraft/testcraft) [![GitHub License](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/CircleCI-Public/gradle-orb/master/LICENSE) [![CircleCI Community](https://img.shields.io/badge/community-CircleCI%20Discuss-343434.svg)](https://discuss.circleci.com/c/ecosystem/orbs)
==============================

- [What is TestCraft cli Orb?](#what-is-testcraft-cli-orb)
- [Usage](#usage)
- [Contributing](#contributing)

### What is TestCraft cli Orb?
  This orb is a cli tool that enables you to execute TestCraft test automation scenarios and view their results through CircleCI’s CI/CD platform.
  

### Usage

For full usage guidelines, refer below:

```description: Simple Test Craft execution from Circle CI

  usage:
    version: 2.1
    orbs:
      testcraft: testcraft/testcraft@volatile

    workflows:
        tc_test:
          jobs:
            - testcraft/run:
                user_mail: ${user_mail}
                platform: ${platform}
                project: ${project}
                suite: ${suite}
                environment: ${environment}
```

### Contributing

We welcome [issues](https://github.com/test-craft/tc-cli-orb/issues) to and [pull requests](https://github.com/test-craft/tc-cli-orb/pulls) against this repository!

For further questions/comments about this or other orbs, visit [CircleCI's orbs discussion forum.](https://discuss.circleci.com/c/ecosystem/orbs/62)