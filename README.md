<div align="center">

# asdf-cni-plugin [![Build](https://github.com/tnosaj/asdf-cni-plugin/actions/workflows/build.yml/badge.svg)](https://github.com/tnosaj/asdf-cni-plugin/actions/workflows/build.yml) [![Lint](https://github.com/tnosaj/asdf-cni-plugin/actions/workflows/lint.yml/badge.svg)](https://github.com/tnosaj/asdf-cni-plugin/actions/workflows/lint.yml)

[cni-plugin](https://github.com/tnosaj/asdf-cni-plugin) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add cni-plugin
# or
asdf plugin add cni-plugin https://github.com/tnosaj/asdf-cni-plugin.git
```

cni-plugin:

```shell
# Show all installable versions
asdf list-all cni-plugin

# Install specific version
asdf install cni-plugin latest

# Set a version globally (on your ~/.tool-versions file)
asdf global cni-plugin latest

# Now cni-plugin commands are available
cni-plugin --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/tnosaj/asdf-cni-plugin/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jason Tevnan](https://github.com/tnosaj/)
