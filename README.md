# TypeTreeGeneratorAPIEx

This is a fork of [TypeTreeGeneratorAPI](https://github.com/UnityPy-Org/TypeTreeGeneratorAPI) with modifications.

You can consume the library via Python bindings or directly in .NET. 

Do note that this package overrides the original package on PyPI i.e. `pip install TypeTreeGeneratorAPIEx` will also install this package as `TypeTreeGeneratorAPI`
## Test Locally
```bash
dotnet restore
# Change your runtime identifier if needed (e.g. linux-x64, osx-x64, win-x64, etc.)
dotnet publish -c Release -r win-x64
# Build Python bindings
cd bindings\python
# Install
pip install .
```