# Useful Reference
- [RStudio hangs with Ubuntu 22.04](https://stackoverflow.com/questions/72088170/rstudio-hangs-on-startup-after-ubuntu-22-04-update)
    * `/usr/lib/rstudio/bin/rstudio --no-sandbox

- Graphics
    - `options(repr.plot.width=8, repr.plot.height=3)`
    - `par(mfrow=c(2,2))`

# JupyterLab Keyboard Shortcuts

- `vi ~/.jupyter/lab/user-settings/@jupyterlab/shortcuts-extension/shortcuts.jupyterlab-settings`
- [Arrow Symbol](https://www.toptal.com/designers/htmlarrows/arrows/)
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
    - <kbd>Alt</kbd> + <kbd>&#8595;</kbd> $\Rightarrow$   `"%>%"`  from `library(magrittr)`
    ```
            {
                "args": {
                    "text": "%>%"
                },
                "command": "notebook:replace-selection",
                "keys": [
                    "Alt ArrowDown"
                ],
                "selector": ".jp-Notebook"
            },

    ```

    - <kbd>Alt</kbd> + <kbd>&#8596;</kbd> $\Rightarrow$   `<-` or `->`
    ```
            {
                "args": {
                    "text": "<-"
                },
                "command": "notebook:replace-selection",
                "keys": [
                    "Alt ArrowLeft"
                ],
                "selector": ".jp-Notebook"
            },
            {
                "args": {
                    "text": "->"
                },
                "command": "notebook:replace-selection",
                "keys": [
                    "Alt ArrowRight"
                ],
                "selector": ".jp-Notebook"
            },
    ```
