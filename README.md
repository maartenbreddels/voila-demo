# voila-demo
Demo for voila

# Run on mybinder
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/maartenbreddels/voila-demo/master?urlpath=voila%2Frender%2Fvoila-vuetify.ipynb)


# Run on heroku

[Voila on Heroku](https://voila-vuetify.herokuapp.com/)


Following instructions from https://github.com/martinRenou/voila_heroku

Or alternatively use https://github.com/jtpio/jupyterlab-heroku

# Run locally
```
$ pip install voila voila-vuetify bqplot numpy ipyvuetify
$ voila --template voila-vuetify --enable_nbextensions=True ./notebooks/voila-vuetify.ipynb
```
