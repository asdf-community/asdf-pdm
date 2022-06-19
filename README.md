<div align="center">

# asdf-pdm [![Build](https://github.com/1oglop1/asdf-pdm/actions/workflows/build.yml/badge.svg)](https://github.com/1oglop1/asdf-pdm/actions/workflows/build.yml) [![Lint](https://github.com/1oglop1/asdf-pdm/actions/workflows/lint.yml/badge.svg)](https://github.com/1oglop1/asdf-pdm/actions/workflows/lint.yml)


[pdm](https://github.com/pdm-project/pdm) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

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
