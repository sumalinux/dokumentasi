# dokumentasi

## Jupyter-Lab

### Extensions enabled

- jupyterlab [git](https://blog.reviewnb.com/jupyterlab-git-extension/) extension

- jupyterlab [lsp](https://github.com/krassowski/jupyterlab-lsp) extension

- jupyterlab [codeium](https://github.com/jtpio/jupyterlab-codeium) extension

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
        jupyterlab_templates v0.5.2 enabled OK (python, jupyterlab_templates)
        nbdime-jupyterlab v3.0.2 enabled OK
        jupyterlab-plotly v5.24.1 enabled  X
        iturtle v0.1.0 enabled  X (python, iturtle)
        jupyterlab_pygments v0.3.0 enabled OK (python, jupyterlab_pygments)
        spreadsheet-editor v0.7.2 enabled OK (python, jupyterlab-spreadsheet-editor)
        jupyterlab-tour v4.0.1 enabled OK (python, jupyterlab-tour)
        @jupyterlab/git v0.50.2 enabled OK (python, jupyterlab-git)
        @jupyter-lsp/jupyterlab-lsp v5.1.0 enabled OK (python, jupyterlab-lsp)
        @jupyter-widgets/jupyterlab-manager v5.0.13 enabled OK (python, jupyterlab_widgets)


   The following extensions may be outdated or specify dependencies that are incompatible with the current version of jupyterlab:
        jupyterlab-plotly
        iturtle

   If you are a user, check if an update is available for these packages.
   If you are a developer, re-run with `--verbose` flag for more details.

Other labextensions (built into JupyterLab)
   app dir: /venv/share/jupyter/lab


Disabled extensions:
    @jupyterlab/completer-extension:base-service
    @jupyterlab/fileeditor-extension:language-server
    @jupyterlab/lsp-extension:settings
    @jupyterlab/notebook-extension:language-server
```

