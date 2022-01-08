<div align="center">

# asdf-osqueryi [![Build](https://github.com/davidecavestro/asdf-osqueryi/actions/workflows/build.yml/badge.svg)](https://github.com/davidecavestro/asdf-osqueryi/actions/workflows/build.yml) [![Lint](https://github.com/davidecavestro/asdf-osqueryi/actions/workflows/lint.yml/badge.svg)](https://github.com/davidecavestro/asdf-osqueryi/actions/workflows/lint.yml)


[osquery](https://github.com/osquery/osquery) interactive [shell](https://osquery.readthedocs.io/en/stable/introduction/using-osqueryi/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add osqueryi
# or
asdf plugin add osqueryi https://github.com/davidecavestro/asdf-osqueryi.git
```

osqueryi:

```shell
# Show all installable versions
asdf list-all osqueryi

# Install specific version
asdf install osqueryi latest

# Set a version globally (on your ~/.tool-versions file)
asdf global osqueryi latest

# Now osqueryi commands are available
osqueryi --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/davidecavestro/asdf-osqueryi/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Davide Cavestro](https://github.com/davidecavestro/)
