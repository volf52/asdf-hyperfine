<div align="center">

# asdf-hyperfine [![Build](https://github.com/volf52/asdf-hyperfine/actions/workflows/build.yml/badge.svg)](https://github.com/volf52/asdf-hyperfine/actions/workflows/build.yml) [![Lint](https://github.com/volf52/asdf-hyperfine/actions/workflows/lint.yml/badge.svg)](https://github.com/volf52/asdf-hyperfine/actions/workflows/lint.yml)

[hyperfine](https://github.com/sharkdp/hyperfine) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities

# Install

Plugin:

```shell
asdf plugin add hyperfine

# or

asdf plugin add hyperfine https://github.com/volf52/asdf-hyperfine.git
```

hyperfine:

```shell
# Show all installable versions
asdf list-all hyperfine

# Install specific version
asdf install hyperfine latest

# Set a version globally (on your ~/.tool-versions file)
asdf global hyperfine latest

# Now hyperfine commands are available
hyperfine --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/volf52/asdf-hyperfine/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Arslan](https://github.com/volf52/)
