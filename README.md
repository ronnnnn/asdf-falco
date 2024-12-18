<div align="center">

# asdf-falco [![Build](https://github.com/ronnnnn/asdf-falco/actions/workflows/build.yml/badge.svg)](https://github.com/ronnnnn/asdf-falco/actions/workflows/build.yml) [![Lint](https://github.com/ronnnnn/asdf-falco/actions/workflows/lint.yml/badge.svg)](https://github.com/ronnnnn/asdf-falco/actions/workflows/lint.yml)

[falco](https://github.com/ysugimoto/falco) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add falco
# or
asdf plugin add falco https://github.com/ronnnnn/asdf-falco.git
```

falco:

```shell
# Show all installable versions
asdf list-all falco

# Install specific version
asdf install falco latest

# Set a version globally (on your ~/.tool-versions file)
asdf global falco latest

# Now falco commands are available
falco -V
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ronnnnn/asdf-falco/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Seiya Kokushi](https://github.com/ronnnnn/)
