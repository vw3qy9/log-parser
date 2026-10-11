# log-parser

A line-oriented log parser that turns key=value logs into dictionaries.

## Why

I kept rewriting the same thirty lines in every project, so I pulled them out.

## Install

```bash
pip install log-parser
```

## Usage

```python
from log_parser import logParser

result = logParser("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
