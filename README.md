# JupyterWebApiDemo
Brief demo of web API for jupyter notebook using ipywidgets, voila, and binder

## Build and interactive noteboook
Use [ipywidgets](https://ipywidgets.readthedocs.io/en/latest/user_install.html) to create interactive user interfaces in your notebook, as in [web_demo.ipynb](./web_demo.ipynb).

## Run a notebook locally
Install [Voila](https://github.com/voila-dashboards/voila)

```
pip install voila
```

Add a ```requirements.txt``` file that includes all the Python dependencies. E.g., for ```web_demo.ipynb```:

```
numpy
ipywidgets
joblib
```

Run the demo notebook as a standalone app, via your browser.
```
voila web_demo.ipynb
```

## Host your notebook on the web
Place your notebook online at a publically available location, such as Github.

Use [Binder](https://mybinder.org/) to host and run your notbook.


