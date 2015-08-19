# Example Binder with requirements.txt

A Binder-compatibible repo with a `requirements.txt` file.

The `requirements.txt` file should list all Python libraries that your notebooks depend on, and they will be installed using 

```
pip install -r requirements.txt
```

Note that many scientific Python libraries (e.g. `numpy`, `scipy`, `sklearn`, etc.) are included already because the [`base`](https://github.com/binder-project/binder/blob/master/images/base/Dockerfile) image for Binder is built on Anaconda.

In this example we include the library `seaborn`, and our notebook uses Seaborn to plot a figure.
