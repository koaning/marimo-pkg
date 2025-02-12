<img src="imgs/icon.png" alt="dicekit logo" width="125" align="right"/>

### marimo-pkg

> Sometimes a Marimo notebook is all you need to build a simple Python package. This project contains a cookiecutter to help you set those projects up.

```
uv run --with cookiecutter cookiecutter https://github.com/koaning/marimo-pkg
```

### How it works 

All the cells in Marimo that carry the `## Export` comment on top are exported as Python code. The Python code is then used to build the package. It's a pattern I am re-using from the [dicekit](https://github.com/koaning/dicekit/) package.
