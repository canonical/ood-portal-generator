# ood-portal-generator

![GitHub License](https://img.shields.io/github/license/canonical/ood-portal-generator)
[![Matrix](https://img.shields.io/matrix/ubuntu-hpc%3Amatrix.org?logo=matrix&label=ubuntu-hpc)](https://matrix.to/#/#hpc:ubuntu.com)

A CLI tool for generating Apache2 configuration files for the
[Open OnDemand](https://openondemand.org) portal.

`generate-ood-portal` renders an Apache2 configuration file using
an `ood_portal.yml` configuration file. It is a lower-level alternative
to the `update_ood_portal` utility shipped with Open OnDemand and is
used by the [Open OnDemand snap](https://github.com/canonical/ondemand-snap).

## ✨ Getting started

### Build

```shell
make build
```

### Usage

```shell
generate-ood-portal --input ood_portal.yml --output ood-portal.conf
```

For more information on available options:

```shell
generate-ood-portal --help
```

## 🤔 What's next?

If you want to learn more about ood-portal-generator,
here are some further resources for you to explore:

* [Open an issue](https://github.com/canonical/ood-portal-generator/issues/new?title=ISSUE+TITLE&body=*Please+describe+your+issue*)
* [Ask a question](https://discourse.ubuntu.com/c/project/hpc/151)

## 🛠️ Development

The project uses [Make](https://www.gnu.org/software/make/) for development,
which provides some useful commands that will help you while hacking on ood-portal-generator:

```shell
make build    # Build the CLI binary
make test     # Run unit tests
make fmt      # Reformat Go source files
make deps     # Install project dependencies
```

If you're interested in contributing your work to ood-portal-generator,
take a look at our [contributing guidelines](./CONTRIBUTING.md) for further details.

## 🤝 Project and community

ood-portal-generator is a project of the [Ubuntu High-Performance Computing community](https://ubuntu.com/community/governance/teams/hpc).
Interested in contributing bug fixes, new editors, documentation, or feedback? Want to join the Ubuntu HPC community? You've come to the right place 🤩

Here's some links to help you get started with joining the community:

* [Ubuntu Code of Conduct](https://ubuntu.com/community/ethos/code-of-conduct)
* [Contributing guidelines](./CONTRIBUTING.md)
* [Join the conversation on Matrix](https://matrix.to/#/#hpc:ubuntu.com)
* [Get the latest news or ask and answer questions on the Ubuntu Discourse](https://discourse.ubuntu.com/c/project/hpc/151)

## 📋 License

ood-portal-generator is free software, distributed under the
GNU General Public License, version 3.0.
See the [GPL-3.0 LICENSE](./LICENSE) file for further details.
