# uv-public-pypackage

This is a test package for a public GitHub repository.

## Usage

```bash
$ uv pip install "uv-public-pypackage@git+https://github.com/astral-test/uv-public-pypackage"
```

## Source

The package was generated with `packse`.

```
packse build-pkg uv-public-pypackage 0.1.0
mv build/uv-public-pypackage/uv-public-pypackage-0.1.0/* .
rm -r build dist
```
