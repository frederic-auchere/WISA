# WISA - WOW

[This Jupyter notebook](wow.ipynb) demonstrates denoising and image enhancement with the *à trous* wavelet transform. Prepared for the [WISA 2023 conference](https://www.wisa2023.org/).

## Installation

You'll need three packages that are not in PyPi, so you'll have to clone them

```shell
git clone https://github.com/frederic-auchere/wavelets.git
cd wavelets
pip .
```

```shell
git clone https://github.com/frederic-auchere/rectify.git
cd rectify
pip install .
```

```shell
git clone https://github.com/frederic-auchere/wow.git
cd wow
pip install .
```

You'll also need ```sunpy``` (only for the official EUI 174 color table)

```shell
pip install sunpy
```
