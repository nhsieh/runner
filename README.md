# Hi PPE Team!

This fork is used in deploying vSphere runners. Specifically this line https://github.com/pivotal/terraforming-vsphere-releng/blob/main/terraforming-pas/scripts/modify_github_action_runner.sh#L54.

We pinned this because the updates to the runners kept breaking. This may not be needed when the Github system is more stable. 

Side note: GCP runners automatically update themselves. This is an anomaly.


# GitHub Actions Runner

[![Actions Status](https://github.com/actions/runner/workflows/Runner%20CI/badge.svg)](https://github.com/actions/runner/actions)
[![Runner E2E Test](https://github.com/actions/runner/workflows/Runner%20E2E%20Test/badge.svg)](https://github.com/actions/runner/actions)

The runner is the application that runs a job from a GitHub Actions workflow. It is used by GitHub Actions in the [hosted virtual environments](https://github.com/actions/virtual-environments), or you can [self-host the runner](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/about-self-hosted-runners) in your own environment.

## Get Started

For more information about installing and using self-hosted runners, see [Adding self-hosted runners](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/adding-self-hosted-runners) and [Using self-hosted runners in a workflow](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/using-self-hosted-runners-in-a-workflow)

Runner releases:

![win](docs/res/win_sm.png) [Pre-reqs](docs/start/envwin.md) | [Download](https://github.com/actions/runner/releases)  

![macOS](docs/res/apple_sm.png)  [Pre-reqs](docs/start/envosx.md) | [Download](https://github.com/actions/runner/releases)  

![linux](docs/res/linux_sm.png)  [Pre-reqs](docs/start/envlinux.md) | [Download](https://github.com/actions/runner/releases)

## Contribute

We accept contributions in the form of issues and pull requests.  [Read more here](docs/contribute.md) before contributing.
