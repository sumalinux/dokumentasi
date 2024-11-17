# dokumentasi

## Jupyter-Lab [jupyter.kalou.net](https://jupyter.kalou.net)

### Extensions enabled

- [git](https://blog.reviewnb.com/jupyterlab-git-extension/) extension

- [jupySQL](https://jupysql.ploomber.io/en/latest/quick-start.html) extension

- [lsp](https://github.com/krassowski/jupyterlab-lsp) extension

- [pyWidgets](https://ipywidgets.readthedocs.io/en/latest) extension

### Features enabled

- Text Editor codefolding (Settings -> Text Editor -> Code Folding)
- Notebook codefolding (Settings -> Notebook -> Code Folding)

#### Keyboard [shortcuts](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/navigation-hotkeys/readme.html)



#### Miscelanous

- check which extensions are activated

```
docker exec -u root -it 2e04914a9139 bash
jupyter:/# . /venv/bin/activate
(venv) jupyter:/# /venv/bin/jupyter labextension list
JupyterLab v4.2.6
/venv/share/jupyter/labextensions
        jupyterlab-ipyflow v0.0.204 enabled  X
        jupyterlab-cell-flash v0.4.0 enabled OK (python, jupyterlab-cell-flash)
        jupyterlab_templates v0.5.2 enabled OK (python, jupyterlab_templates)
        jupyterlabcodetoc v4.0.1 enabled OK (python, jupyterlabcodetoc)
        nbdime-jupyterlab v3.0.2 enabled OK
        iturtle v0.1.0 enabled  X (python, iturtle)
        jupyterlab_pygments v0.3.0 enabled OK (python, jupyterlab_pygments)
        jupyterlab-theme-solarized-dark v3.0.1 enabled OK (python, jupyterlab_theme_solarized_dark)
        jupysql-plugin v0.4.5 enabled  X (python, jupysql-plugin)
        ipytone v0.5.1 enabled OK (python, ipytone)
        spreadsheet-editor v0.7.2 enabled OK (python, jupyterlab-spreadsheet-editor)
        jupyterlab-tour v4.0.1 enabled OK (python, jupyterlab-tour)
        anywidget v0.9.13 enabled OK
        jupyterlab_autosave_on_focus_change v0.4.1 enabled OK (python, jupyterlab_autosave_on_focus_change)
        @jupyterlab/git v0.50.2 enabled OK (python, jupyterlab-git)
        @jupyter-lsp/jupyterlab-lsp v5.1.0 enabled OK (python, jupyterlab-lsp)
        @jupyter-notebook/lab-extension v7.2.2 enabled OK
        @jupyter-widgets/jupyterlab-manager v5.0.13 enabled OK (python, jupyterlab_widgets)
        @ouyangde1/jupyterlab-spreadsheet v0.4.2 enabled OK
        @widgetti/jupyter-react v0.4.2 enabled OK (python, ipyreact)


   The following extensions may be outdated or specify dependencies that are incompatible with the current version of jupyterlab:
        jupyterlab-ipyflow
        iturtle
        jupysql-plugin

   If you are a user, check if an update is available for these packages.
   If you are a developer, re-run with `--verbose` flag for more details.


Disabled extensions:
    @jupyterlab/completer-extension:base-service
    @jupyterlab/fileeditor-extension:language-server
    @jupyterlab/lsp-extension:settings
    @jupyterlab/notebook-extension:language-server
(venv) jupyter:/#
```

#### See ALSO

Wiki - [Jupyter Lab Developpment](https://github.com/sumalinux/dokumentasi/wiki/Home-‐-Jupyter-Lab-Developpement)
