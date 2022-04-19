<div align="center">

# asdf-lazygit [![Build](https://github.com/nklmilojevic/asdf-lazygit/actions/workflows/build.yml/badge.svg)](https://github.com/nklmilojevic/asdf-lazygit/actions/workflows/build.yml) [![Lint](https://github.com/nklmilojevic/asdf-lazygit/actions/workflows/lint.yml/badge.svg)](https://github.com/nklmilojevic/asdf-lazygit/actions/workflows/lint.yml)


[lazygit](https://github.com/jesseduffield/lazygit) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add lazygit
# or
asdf plugin add lazygit https://github.com/nklmilojevic/asdf-lazygit.git
```

lazygit:

```shell
# Show all installable versions
asdf list-all lazygit

# Install specific version
asdf install lazygit latest

# Set a version globally (on your ~/.tool-versions file)
asdf global lazygit latest

# Now lazygit commands are available
lazygit --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/nklmilojevic/asdf-lazygit/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Nikola Milojević](https://github.com/nklmilojevic/)
