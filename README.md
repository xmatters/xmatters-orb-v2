# xmatters-orb Orb [![CircleCI Build Status](https://circleci.com/gh/xmatters/xmatters-orb-v2.svg?style=shield "CircleCI Build Status")](https://circleci.com/gh/xmatters/xmatters-orb-v2) [![CircleCI Orb Version](https://img.shields.io/badge/endpoint.svg?url=https://badges.circleci.io/orb/xmatters/xmatters-orb)](https://circleci.com/orbs/registry/orb/xmatters/xmatters-orb) [![GitHub License](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/xmatters/xmatters-orb-v2/master/LICENSE) [![CircleCI Community](https://img.shields.io/badge/community-CircleCI%20Discuss-343434.svg)](https://discuss.circleci.com/c/ecosystem/orbs)

Utilize this orb to easily add xMatters to your CI/CD pipeline.

## Usage

`xmatters/xmatters-orb@x.y`

Example use-cases are provided on the orb [registry page](https://circleci.com/orbs/registry/orb/xmatters/xmatters-orb#usage-examples). Source for these examples can be found within the `src/examples` directory.


## Resources

[CircleCI Orb Registry Page](https://circleci.com/orbs/registry/orb/xmatters/xmatters-orb) - The official registry page of this orb for all versions, and commands described.  
[CircleCI Orb Docs](https://circleci.com/docs/2.0/orb-intro/#section=configuration) - Docs for using and creating CircleCI Orbs.  

### How To Contribute

We welcome [issues](https://github.com/xmatters/xmatters-orb-v2/issues) to and [pull requests](https://github.com/xmatters/xmatters-orb-v2/pulls) against this repository!

To publish a new production version:
* Create a PR to the `Alpha` branch with your changes. This will act as a "staging" branch.
* When ready to publish a new production version, create a PR from `Alpha` to `master`. The Git Subject should include `[semver:patch|minor|release|skip]` to indicate the type of release.
* On merge, the release will be published to the orb registry automatically.

For further questions/comments about this or other orbs, visit the Orb Category of [CircleCI Discuss](https://discuss.circleci.com/c/orbs).
