# Useful Tricks

- `options(repr.plot.width=8, repr.plot.height=3)`
- `par(mfrow=c(2,2))`

# JupyterLab Keyboard Shortcuts

- `vi ~/.jupyter/lab/user-settings/@jupyterlab/shortcuts-extension/shortcuts.jupyterlab-settings`

- <kbd>Alt</kbd> + <kbd>&#8593;</kbd> $\Rightarrow$   `"%%R"` (mostly for  `%load_ext rpy2.ipython`)
```
    "shortcuts": [
        {
            "args": {
                "text": "%%R "
            },
            "command": "notebook:replace-selection",
            "keys": [
                "Alt ArrowUp"
            ],
            "selector": ".jp-Notebook"
        },
```

