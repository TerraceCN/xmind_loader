# XMind Loader

XMind loader for langchain

## Usage

Use it programmatically:

```python
from xmind_loader import XMindLoader

docs = XMindLoader("input.xmind").load()
```

or by cli:

```shell
python xmind_loader.py -o output.md input.xmind
```

## XMind Compatibility

Tested on `XMind 23.09.11172` and `XMind 8 Update 9 (R3.7.9.201912052356)`.

Other version may not be compatible. Please open an issue with your incompatible xmind file and version of the xmind you use.
