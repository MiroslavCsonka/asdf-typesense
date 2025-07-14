<div align="center">

# asdf-typesense [![Build](https://github.com/MiroslavCsonka/asdf-typesense/actions/workflows/build.yml/badge.svg)](https://github.com/MiroslavCsonka/asdf-typesense/actions/workflows/build.yml) [![Lint](https://github.com/MiroslavCsonka/asdf-typesense/actions/workflows/lint.yml/badge.svg)](https://github.com/MiroslavCsonka/asdf-typesense/actions/workflows/lint.yml)

[Typesense](https://typesense.org) plugin for the [Mise version manager](https://mise.jdx.dev) (compatible with asdf).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- macOS Ventura (13.x) or newer for macOS users
- Linux (Ubuntu, Debian, CentOS, etc.) with glibc 2.17 or newer
- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html)
- Mise (or asdf) installed

# Install

Plugin:

```shell
mise plugins install typesense
# or
mise plugins install typesense https://github.com/MiroslavCsonka/asdf-typesense.git
```

Typesense:

```shell
# Show all installable versions
mise ls-remote typesense

# Install specific version
mise install typesense 0.25.2

# Set a version globally (on your ~/.tool-versions file)
mise global typesense 0.25.2

# Now typesense-server commands are available
typesense-server --version
```

Check [Mise](https://mise.jdx.dev) readme for more instructions on how to install & manage versions.

## Supported Platforms
- **macOS**: Intel (amd64) and Apple Silicon (arm64) - requires macOS Ventura (13.x) or newer
- **Linux**: amd64 and arm64 architectures - requires glibc 2.17 or newer

## Notes
- Versions are fetched from Typesense GitHub releases
- Pre-built binaries are downloaded from dl.typesense.org
- For unsupported platforms or older OS versions, use Docker instead

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/MiroslavCsonka/asdf-typesense/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Miroslav Csonka](https://github.com/MiroslavCsonka/)
