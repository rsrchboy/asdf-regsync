<div align="center">

# asdf-regsync [![Build](https://github.com/rsrchboy/asdf-regsync/actions/workflows/build.yml/badge.svg)](https://github.com/rsrchboy/asdf-regsync/actions/workflows/build.yml) [![Lint](https://github.com/rsrchboy/asdf-regsync/actions/workflows/lint.yml/badge.svg)](https://github.com/rsrchboy/asdf-regsync/actions/workflows/lint.yml)

[regsync](https://github.com/regclient/regclient) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add regsync
# or
asdf plugin add regsync https://github.com/rsrchboy/asdf-regsync.git
```

regsync:

```shell
# Show all installable versions
asdf list-all regsync

# Install specific version
asdf install regsync latest

# Set a version globally (on your ~/.tool-versions file)
asdf global regsync latest

# Now regsync commands are available
regsync version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/rsrchboy/asdf-regsync/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Chris Weyl](https://github.com/rsrchboy/)
