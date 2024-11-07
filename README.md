# dokumentasi

## Jupyter-Lab

### Extensions enabled

- jupyterlab [git](https://blog.reviewnb.com/jupyterlab-git-extension/) extension

- jupyterlab [lsp](https://github.com/krassowski/jupyterlab-lsp) extension

### Features enabled

- Text Editor codefolding (Settings -> Text Editor -> Code Folding)
- Notebook codefolding (Settings -> Notebook -> Code Folding)


#### Miscelanous

- check which extensions are activated

```
jupyter:/# /venv/bin/jupyter labextension list
JupyterLab v4.3.0
/venv/share/jupyter/labextensions
        jupyterlab-codeium v0.1.1 enabled OK (python, jupyterlab_codeium)
        nbdime-jupyterlab v3.0.2 enabled OK
        jupyterlab-plotly v5.24.1 enabled  X
        jupyterlab_pygments v0.3.0 enabled OK (python, jupyterlab_pygments)
        jupyterlab-tour v4.0.1 enabled OK (python, jupyterlab-tour)
        @lckr/jupyterlab_variableinspector v3.2.4 enabled  X (python, lckr_jupyterlab_variableinspector)
        @jupyterlab/git v0.50.2 enabled OK (python, jupyterlab-git)
        @jupyter-lsp/jupyterlab-lsp v5.1.0 enabled OK (python, jupyterlab-lsp)


   The following extensions may be outdated or specify dependencies that are incompatible with the current version of jupyterlab:
        jupyterlab-plotly
        @lckr/jupyterlab_variableinspector

   If you are a user, check if an update is available for these packages.
   If you are a developer, re-run with `--verbose` flag for more details.


Disabled extensions:
    @jupyterlab/completer-extension:base-service
    @jupyterlab/fileeditor-extension:language-server
    @jupyterlab/lsp-extension:settings
    @jupyterlab/notebook-extension:language-server
```

