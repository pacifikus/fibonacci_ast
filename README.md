# fibonacci_ast

[![Code style](https://github.com/pacifikus/fibonacci_ast/actions/workflows/style.yml/badge.svg)](https://github.com/pacifikus/flake8-global-variables/actions/workflows/style.yml)
[![Python Version](https://img.shields.io/pypi/pyversions/fib-ast.svg)](https://pypi.org/project/fib-ast/)
[![PyPI version](https://badge.fury.io/py/fib-ast.svg)](https://pypi.org/project/fib-ast/)

## Installation

```bash
pip install fib-ast
```

## Code example

Creation Fibonacci function AST graph:

```python
from fib_ast import get_ast_image

ast_image_path = 'ast.png'
get_ast_image(filepath=ast_image_path)
```

## License

MIT.

