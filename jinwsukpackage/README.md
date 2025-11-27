# pypiguide

A starter project for creating a Python package.

## Installation

### Development Setup

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

pip install -e .
```

### From PyPI

```bash
pip install pypiguide
```

## Usage

```python
from pypiguide import hello

print(hello())  # Output: Hello, World!
```

## Development

### Building the Package

```bash
pip install --upgrade build twine
python -m build
```

### Publishing to PyPI

```bash
twine upload dist/*
```

## License

See LICENSE file for details.