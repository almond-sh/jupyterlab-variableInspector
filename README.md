# jupyterlab_variableinspector - Almond flavored

[![Github Actions Status](https://github.com/almond-sh/jupyterlab-variableInspector/workflows/Build/badge.svg)](https://github.com/almond-sh/jupyterlab-variableInspector/actions?query=workflow%3ABuild)
[![npm version](https://badge.fury.io/js/%40almond-sh%2Fjupyterlab_variableinspector.svg)](https://badge.fury.io/js/%40almond-sh%2Fjupyterlab_variableinspector)

This extension is a customized version of the original
[jupyterlab_variableinspector](https://github.com/almond-sh/jupyterlab-variableInspector), that works with [Almond](https://github.com/almond-sh/almond).

Install it with
```text
$ jupyter labextension install @almond-sh/jupyterlab_variableinspector
```

Then pass `--variable-inspector` as an option when installing Almond (>= `0.10.9`):
```text
$ cs launch almond -- --variable-inspector --install
```

Lastly, start JupyterLab, and open the variable inspector panel by right-clicking in a cell, then "Open Variable Inspector".
