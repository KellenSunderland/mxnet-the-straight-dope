# Run these tutorials

Each tutorial is made from a Jupyter notebook, which is editable and
runable. Assume `python` in already installed, then in additional, both
`jupyter` and a recent version of `mxnet` are required.  The following
commands install them through `pip`:

```bash
# optional: update pip to the newest version
sudo pip install --upgrade pip
# install jupyter
pip install jupyter --user
# install the nightly built mxnet
pip install mxnet --pre --user
```

The default `MXNet` package only supports CPU while some tutorials may need
GPUs. If GPU is available and either CUDA 7.5 or 8.0 is installed, then we can
install the GPU-supported package

```bash
pip install mxnet-cu75 --pre --user  # for CUDA 7.5
pip install mxnet-cu80 --pre --user  # for CUDA 8.0
```

Now we are ready to obtain the source codes and run them

```bash
git clone https://github.com/zackchase/mxnet-the-straight-dope/
cd mxnet-the-straight-dope
jupyter notebook
```

The last command starts the jupyter notebook, and now you can edit and run these
tutorials now.
