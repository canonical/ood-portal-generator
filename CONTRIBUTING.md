# Contributing to `ood-portal-generator`

Do you want to contribute to the `ood-portal-generator` repository? You've come to the right place then!
__Here is how you can get involved.__

Before you start working on your contribution, please familiarize yourself with the [Charmed
HPC project's contributing guide]. After you've gone through the main contributing guide,
you can use this guide for specific information on contributing to the `ood-portal-generator` repository.

Have any questions? Feel free to ask them in the [Ubuntu High-Performance Computing Matrix chat]
or in the [High-Performance Computing category on the Ubuntu Discourse].

[Charmed HPC project's contributing guide]: https://github.com/canonical/hpc-team/blob/main/CONTRIBUTING.md
[Ubuntu High-Performance Computing Matrix chat]: https://matrix.to/#/#hpc:ubuntu.com
[High-Performance Computing category on the Ubuntu Discourse]: https://discourse.ubuntu.com/c/project/hpc/151

## Hacking on `ood-portal-generator`

This repository uses [Make](https://www.gnu.org/software/make/) for development
which provides some useful commands that will help you while hacking on `ood-portal-generator`:

```shell
# Build the CLI binary
make build

# Install project dependencies
make deps
```

Run `make help` to view the full list of available targets.

### Before opening a pull request on the `ood-portal-generator` repository

Ensure that your changes pass all the existing tests, and that you have added tests
for any new features you're introducing in this changeset.

Your proposed changes will not be reviewed until your changes pass all the
required tests. You can run the required tests locally using `make`:

```shell
# Reformat Go source files
make fmt

# Run unit tests
make test
```

## License information

By contributing to `ood-portal-generator`, you agree to license your contribution under
the GNU General Public License v3.0.

### Adding a new file to `ood-portal-generator`

If you add a new source code file to the repository, add the following license header
as a comment to the top of the file with the copyright owner set to the organization
you are contributing on behalf of and the current year set as the copyright year.

```text
Copyright [yyyy] [name of copyright owner]

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
```

### Updating an existing file in `ood-portal-generator`

If you are making changes to an existing file, and the copyright year is not the current year,
update the year range to include the current year. For example, if a file's copyright year is:

```text
Copyright 2024 Canonical Ltd.
```

and you make changes to that file in 2026, update the copyright year in the file to:

```text
Copyright 2024-2026 Canonical Ltd.
```
