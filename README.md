# pre-commit-luacheck

Lints Lua files using [Luacheck](https://luacheck.readthedocs.io/en/stable/).

## Installation

This hook is meant to be used with [pre-commit](https://pre-commit.com/).

Add the following hook to `.pre-commit-config.yaml`:

```yaml
  - repo: https://github.com/Calinou/pre-commit-luacheck
    rev: v1.0.0
    hooks:
      - id: luacheck
```

## License

Copyright © 2019 Hugo Locurcio and contributors

Unless otherwise specified, files in this repository are licensed under
the MIT license; see [LICENSE.md](LICENSE.md) for more information.
