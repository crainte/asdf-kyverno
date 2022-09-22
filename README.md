<div align="center">

# asdf-kyverno [![Build](https://github.com/crainte/asdf-kyverno/actions/workflows/build.yml/badge.svg)](https://github.com/crainte/asdf-kyverno/actions/workflows/build.yml) [![Lint](https://github.com/crainte/asdf-kyverno/actions/workflows/lint.yml/badge.svg)](https://github.com/crainte/asdf-kyverno/actions/workflows/lint.yml)


[kyverno](https://kyverno.io/docs/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add kyverno
# or
asdf plugin add kyverno https://github.com/crainte/asdf-kyverno.git
```

kyverno:

```shell
# Show all installable versions
asdf list-all kyverno

# Install specific version
asdf install kyverno latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kyverno latest

# Now kyverno commands are available
kyverno version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/crainte/asdf-kyverno/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Chris Alexander](https://github.com/crainte/)
