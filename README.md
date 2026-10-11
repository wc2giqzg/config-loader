# config-loader

Merge configuration from files, environment variables and defaults.

## Why

Extracted from a larger codebase where it had grown organically.

## Install

```bash
pip install config-loader
```

## Usage

```python
from config_loader import configLoader

result = configLoader("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
