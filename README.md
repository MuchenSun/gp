> This tutorial is heavily based on Dan Foreman-Mackey's original amazing hands-on GP tutorial, which literally helps me enter the world of GP. After finishing the tutorial, as a reader/user myself, I think this tutorial might be even more helpful if I could include more details, so here we are.

> Compared with original version, here I added more explanation about multi-variate Gaussian distribution, the role of covariance matrix, and exposed more details of regression with GP. Below is the original README from Dan Foreman-Mackey.

This repository contains an interactive IPython worksheet (`worksheet.ipynb`)
designed to introduce you to Gaussian Process models. Only very minimal
experience with Python should be necessary to get something out of this.

Some of this worksheet was originally prepared for a lab section at the Penn
State Astrostats summer school in 2014 and it has been updated and adapted
several times since then.

**Remember**: the best reference for anything related to Gaussian Processes is
[Rasmussen & Williams](http://www.gaussianprocess.org/gpml/).


Prerequisites
-------------

You'll need the standard scientific Python stack (numpy, scipy, and
matplotlib), a recent (3+) version of [IPython/Jupyter](http://jupyter.org/)
(including the notebook), and [emcee](http://dfm.io/emcee) installed. If you
don't already have a working Python installation (and maybe even if you do), I
recommend using the [Anaconda distribution](http://continuum.io/downloads) and
then running `pip install emcee`.

Also, this tutorial has several sections using jupyter widgets, please refer [**here**](https://ipywidgets.readthedocs.io/en/latest/index.html) to install and configure. Configuration may depend on system and may differ from jupyter-notebook and jupyter-lab.

Usage
-----

After you have your Python environment set up, download the code from this
repository by running:

```
git clone https://github.com/dfm/gp.git
```

or by [clicking here](https://github.com/dfm/gp/archive/master.zip).

Then, navigate into the `gp` directory and run

```
cp worksheet.ipynb worksheet_in_progress.ipynb
jupyter notebook
```

This might open a web browser with the correct URL, but if not, you can copy
and paste the URL that it prints to the terminal into your browser.
Click on `worksheet_in_progress.ipynb` to get started.


License
-------

This repository and the worksheet are copyright 2015-2017 Dan Foreman-Mackey and
they are made available under the terms of the MIT license.
