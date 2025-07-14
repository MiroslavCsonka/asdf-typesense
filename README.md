<div align="center">

# asdf-typesense [![Build](https://github.com/MiroslavCsonka/asdf-typesense/actions/workflows/build.yml/badge.svg)](https://github.com/MiroslavCsonka/asdf-typesense/actions/workflows/build.yml) [![Lint](https://github.com/MiroslavCsonka/asdf-typesense/actions/workflows/lint.yml/badge.svg)](https://github.com/MiroslavCsonka/asdf-typesense/actions/workflows/lint.yml)

[typesense](https://typesense.org) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add typesense
# or
asdf plugin add typesense https://github.com/MiroslavCsonka/asdf-typesense.git
```

typesense:

```shell
# Show all installable versions
asdf list-all typesense

# Install specific version
asdf install typesense latest

# Set a version globally (on your ~/.tool-versions file)
asdf global typesense latest

# Now typesense commands are available
typesense-server --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/MiroslavCsonka/asdf-typesense/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Miroslav Csonka](https://github.com/MiroslavCsonka/)
