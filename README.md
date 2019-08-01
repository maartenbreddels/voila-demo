# voila-demo

Demo using ipyuetify widget and bqplot, and render them with voila and a custom template (voila-vuetifuy) to create a responsive interactive webpage that even works on mobile.

# Screen capture
![img](https://user-images.githubusercontent.com/1765949/61897777-1bae6280-af18-11e9-8fd0-7243510f2e1e.gif)

# Links
 * https://github.com/QuantStack/voila/ (render a Jupyter notebook as webpage/dashboard)
 * https://github.com/mariobuikhuizen/ipyvuetify (Vuetify based ipywidget library)
 * https://github.com/QuantStack/voila-vuetify (Vuetify template for voila)
 * https://github.com/bloomberg/bqplot/ (Interactive plotting library for ipywidget)
 * https://github.com/jupyter-widgets/ipywidgets (Coolest Jupyter framework to create bidirectional browser-kernel widgets)

# Run on mybinder
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/maartenbreddels/voila-demo/master?urlpath=voila%2Frender%2Fvoila-vuetify.ipynb)


# Run on heroku

[Voila on Heroku](https://voila-vuetify.herokuapp.com/)


Following instructions from https://github.com/martinRenou/voila_heroku

Or alternatively use https://github.com/jtpio/jupyterlab-heroku

# Run on Google App Engine

[Voila on App Engine](https://voila-demo.appspot.com/)

Following instructions at https://voila.readthedocs.io/en/latest/deploy.html


# Run locally
```
$ pip install voila voila-vuetify bqplot numpy ipyvuetify
$ voila --template voila-vuetify --enable_nbextensions=True ./notebooks/voila-vuetify.ipynb
```
