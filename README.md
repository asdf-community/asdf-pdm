<div align="center">

# asdf-pdm [![build_svg]][build_yml] [![lint_svg]][lint_yml]


[pdm](https://github.com/pdm-project/pdm) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `curl`, `python3.7+`

# Install

Plugin:

```shell
asdf plugin add pdm
# or
asdf plugin add pdm https://github.com/1oglop1/asdf-pdm.git
```

pdm:

```shell
# Show all installable versions
asdf list-all pdm

# Install specific version
asdf install pdm latest

# Set a version globally (on your ~/.tool-versions file)
asdf global pdm latest

# Now pdm commands are available
pdm --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/1oglop1/asdf-pdm/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jan Gazda](https://github.com/1oglop1/)


[lint_yml]: https://github.com/1oglop1/asdf-pdm/actions/workflows/lint.yml
[lint_svg]: https://github.com/1oglop1/asdf-pdm/actions/workflows/lint.yml/badge.svg

[build_yml]: https://github.com/1oglop1/asdf-pdm/actions/workflows/build.yml
[build_svg]: https://github.com/1oglop1/asdf-pdm/actions/workflows/build.yml/badge.svg
