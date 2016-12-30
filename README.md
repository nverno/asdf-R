# asdf-R

[![Build Status](https://travis-ci.org/nverno/asdf-R.svg?branch=master)](https://travis-ci.org/nverno/asdf-R)

R plugin for [asdf](https://github.com/asdf-vm/asdf) version manager.

## Install

```
asdf plugin-add R https://github.com/nverno/asdf-R.git
```

## Use

Check [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to
install & manage versions of R.

When installing R using `asdf install`, you can pass custom configure options
with the following env vars:

* `R_CONFIGURE_OPTIONS` - use only your configure options
* `R_EXTRA_CONFIGURE_OPTIONS` - append these configure options along with ones
that this plugin already uses (`--enable-R-shlib --prefix-path --with-blas --with-lapack`)

