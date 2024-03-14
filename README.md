<div align="center">

# asdf-yamlscript [![Build](https://github.com/FeryET/asdf-yamlscript/actions/workflows/build.yml/badge.svg)](https://github.com/FeryET/asdf-yamlscript/actions/workflows/build.yml) [![Lint](https://github.com/FeryET/asdf-yamlscript/actions/workflows/lint.yml/badge.svg)](https://github.com/FeryET/asdf-yamlscript/actions/workflows/lint.yml)

[yamlscript](<TOOL HOMEPAGE>) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [asdf-yamlscript  ](#asdf-yamlscript--)
- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add yamlscript
# or
asdf plugin add yamlscript https://github.com/FeryET/asdf-yamlscript.git
```

yamlscript:

```shell
# Show all installable versions
asdf list-all yamlscript

# Install specific version
asdf install yamlscript latest

# Set a version globally (on your ~/.tool-versions file)
asdf global yamlscript latest

# Now yamlscript commands are available
ys --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/FeryET/asdf-yamlscript/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Farhood Etaati](https://github.com/FeryET/)
