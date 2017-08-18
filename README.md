## :dash: :dash: **The Binder Project is moving to a [new repo](https://github.com/jupyterhub/binderhub).** :dash: :dash:

:books: Same functionality. Better performance for you. :books:

Over the past few months, we've been improving Binder's architecture and infrastructure. We're retiring this repo as it will no longer be actively developed. Future development will occur under the [JupyterHub](https://github.com/jupyterhub/) organization.

* All development of the Binder technology will occur in the [binderhub repo](https://github.com/jupyterhub/binderhub)
* Documentation for *users* will occur in the [jupyterhub binder repo](https://github.com/jupyterhub/binder) 
* All conversations and chat for users will occur in the [jupyterhub binder gitter channel](https://gitter.im/jupyterhub/binder)

Thanks for updating your bookmarked links.

## :dash: :dash: **The Binder Project is moving to a [new repo](https://github.com/jupyterhub/binderhub).** :dash: :dash:

---

# Example Binder with requirements.txt

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/binder-project/example-requirements)

A Binder-compatible repo with a `requirements.txt` file.

The `requirements.txt` file should list all Python libraries that your notebooks depend on, and they will be installed using

```
pip install -r requirements.txt
```

Note that many scientific Python libraries (e.g. `numpy`, `scipy`, `sklearn`, etc.) are included already because the [`base`](https://github.com/binder-project/binder-build-core/blob/master/images/base/Dockerfile) image for Binder is built on Anaconda.

In this example we include the library `seaborn`, and our notebook uses Seaborn to plot a figure.
