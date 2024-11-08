<div align="center">

# asdf-ekdo [![Build](https://github.com/mecha-hq/asdf-ekdo/actions/workflows/build.yml/badge.svg)](https://github.com/mecha-hq/asdf-ekdo/actions/workflows/build.yml) [![Lint](https://github.com/mecha-hq/asdf-ekdo/actions/workflows/lint.yml/badge.svg)](https://github.com/mecha-hq/asdf-ekdo/actions/workflows/lint.yml)

[ekdo](https://github.com/mecha-hq/ekdo) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add ekdo
# or
asdf plugin add ekdo https://github.com/mecha-hq/asdf-ekdo.git
```

ekdo:

```shell
# Show all installable versions
asdf list-all ekdo

# Install specific version
asdf install ekdo latest

# Set a version globally (on your ~/.tool-versions file)
asdf global ekdo latest

# Now ekdo commands are available
ekdo --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mecha-hq/asdf-ekdo/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Mecha HQ](https://github.com/mecha-hq/)
