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

- macOS Ventura (13.x) or newer (Typesense binary requirement).
- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- Mise (or asdf) installed.

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

Check [Mise](https://mise.jdx.dev) readme for more instructions on how to install & manage versions. Supports amd64 (Intel) and arm64 (Apple Silicon). For CI (e.g., GitHub Actions), use in macOS runners.

## Notes
- Versions are fetched from Typesense GitHub releases.
- Requires no additional dependencies beyond curl (available on macOS).
- For older macOS, use Docker instead (per Typesense docs).

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/MiroslavCsonka/asdf-typesense/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Miroslav Csonka](https://github.com/MiroslavCsonka/)
