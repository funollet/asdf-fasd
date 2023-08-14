<div align="center">

# asdf-fasd [![Build](https://github.com/funollet/asdf-fasd/actions/workflows/build.yml/badge.svg)](https://github.com/funollet/asdf-fasd/actions/workflows/build.yml) [![Lint](https://github.com/funollet/asdf-fasd/actions/workflows/lint.yml/badge.svg)](https://github.com/funollet/asdf-fasd/actions/workflows/lint.yml)

[fasd](https://github.com/clvv/fasd) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add fasd
# or
asdf plugin add fasd https://github.com/funollet/asdf-fasd.git
```

fasd:

```shell
# Show all installable versions
asdf list-all fasd

# Install specific version
asdf install fasd latest

# Set a version globally (on your ~/.tool-versions file)
asdf global fasd latest

# Now fasd commands are available
fasd -h
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/funollet/asdf-fasd/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jordi Funollet](https://github.com/funollet/)
