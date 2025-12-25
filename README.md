<div align="center">

# asdf-wtp [![Build](https://github.com/ouest/asdf-wtp/actions/workflows/build.yml/badge.svg)](https://github.com/ouest/asdf-wtp/actions/workflows/build.yml) [![Lint](https://github.com/ouest/asdf-wtp/actions/workflows/lint.yml/badge.svg)](https://github.com/ouest/asdf-wtp/actions/workflows/lint.yml)

[wtp](https://github.com/satococoa/wtp) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add wtp
# or
asdf plugin add wtp https://github.com/ouest/asdf-wtp.git
```

wtp:

```shell
# Show all installable versions
asdf list all wtp

# Install specific version
asdf install wtp latest

# Set a version globally (on your ~/.tool-versions file)
asdf set -u wtp latest

# Now wtp commands are available
wtp --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ouest/asdf-wtp/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [ouest](https://github.com/ouest/)
