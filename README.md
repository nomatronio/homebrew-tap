# Nomatron Homebrew Tap

Official Homebrew tap for Nomatron release packages.

## Install

```sh
brew install nomatronio/tap/nomatron
```

```sh
brew install nomatronio/tap/nomatron-connectivity-agent
```

The former `nomatron-agent` formula was renamed to `nomatron-connectivity-agent`; `brew upgrade` migrates existing installs automatically.

## Upgrade

```sh
brew update
brew upgrade nomatron
```

```sh
brew update
brew upgrade nomatron-connectivity-agent
```

## About Nomatron

Nomatron is a deployment and operations platform for teams running HashiCorp Nomad. It provides a UI, CLI, API, GitHub workflows, RBAC, approvals, environments, and operational tooling for managing Nomad application delivery.

## Releases

Release archives are published from the public Nomatron releases repository:

[https://github.com/nomatronio/nomatron-releases](https://github.com/nomatronio/nomatron-releases)

The public release download endpoint is:

[https://get.nomatron.io](https://get.nomatron.io)

## Documentation

Documentation and install guides are available at:

[https://nomatron.io/docs](https://nomatron.io/docs)

## License

Nomatron is proprietary software. Use of Nomatron is governed by the Nomatron license terms.
