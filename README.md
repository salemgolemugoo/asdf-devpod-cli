<div align="center">

# asdf-devpod-cli [![Build](https://github.com/salemgolemugoo/asdf-devpod-cli/actions/workflows/build.yml/badge.svg)](https://github.com/salemgolemugoo/asdf-devpod-cli/actions/workflows/build.yml) [![Lint](https://github.com/salemgolemugoo/asdf-devpod-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/salemgolemugoo/asdf-devpod-cli/actions/workflows/lint.yml)

[devpod-cli](https://github.com/salemgolemugoo/asdf-devpod-cli) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add devpod-cli
# or
asdf plugin add devpod-cli https://github.com/salemgolemugoo/asdf-devpod-cli.git
```

devpod-cli:

```shell
# Show all installable versions
asdf list-all devpod-cli

# Install specific version
asdf install devpod-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global devpod-cli latest

# Now devpod-cli commands are available
devpod version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/salemgolemugoo/asdf-devpod-cli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Marat Salimzianov](https://github.com/salemgolemugoo/)
