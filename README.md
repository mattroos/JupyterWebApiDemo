[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mattroos/JupyterWebApiDemo/HEAD?filepath=.%2Fweb_demo.ipynb)

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

## Host your notebook online
Use [Binder](https://mybinder.org/) to host your interactive notebook.

Note that when you point binder to your repo and notebook, the "Path to a notebook file" should include the voila rendering, so the path should look something like this:

```/voila/render/web_demo.ipynb```

See the [Deployment on Binder](https://voila.readthedocs.io/en/stable/deploy.html) guide for more info.

You may also want to include a ```jupyter_config.json``` file in the repo root directory, to customize the Voila render, e.g.:
```
{
  "VoilaConfiguration": {
    "theme": "dark",
    "template": "gridstack"
  }
}
```









