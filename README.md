<div align="center">

# asdf-pv-migrate [![Build](https://github.com/gwelican/asdf-pv-migrate/actions/workflows/build.yml/badge.svg)](https://github.com/gwelican/asdf-pv-migrate/actions/workflows/build.yml) [![Lint](https://github.com/gwelican/asdf-pv-migrate/actions/workflows/lint.yml/badge.svg)](https://github.com/gwelican/asdf-pv-migrate/actions/workflows/lint.yml)

[pv-migrate](https://github.com/utkuozdemir/pv-migrate) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add pv-migrate
# or
asdf plugin add pv-migrate https://github.com/gwelican/asdf-pv-migrate.git
```

pv-migrate:

```shell
# Show all installable versions
asdf list-all pv-migrate

# Install specific version
asdf install pv-migrate latest

# Set a version globally (on your ~/.tool-versions file)
asdf global pv-migrate latest

# Now pv-migrate commands are available
pv-migrate --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/gwelican/asdf-pv-migrate/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Peter Varsanyi](https://github.com/gwelican/)
