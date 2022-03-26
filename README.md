<div align="center">

# asdf-pnpm [![Build](https://github.com/technikhil314/asdf-pnpm/actions/workflows/build.yml/badge.svg)](https://github.com/technikhil314/asdf-pnpm/actions/workflows/build.yml) [![Lint](https://github.com/technikhil314/asdf-pnpm/actions/workflows/lint.yml/badge.svg)](https://github.com/technikhil314/asdf-pnpm/actions/workflows/lint.yml)

[pnpm](https://pnpm.io/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add pnpm https://github.com/technikhil314/asdf-pnpm.git
```

pnpm:

```shell
# Show all installable versions
asdf list-all pnpm

# Install specific version
asdf install pnpm latest

# Set a version globally (on your ~/.tool-versions file)
asdf global pnpm latest

# Now pnpm commands are available
pnpm --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/technikhil314/asdf-pnpm/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Nikhil Mehta](https://github.com/technikhil314/)
