# btracer


<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

## Install

``` sh
pip install btracer
```

## How to use

``` python
import arviz as az
import btracer

idata = az.from_netcdf('./traces/trace.nc')
btracer.plot_diagnostics(idata)
```

or

``` sh
streamlit run btracer.py traces/
```

## Local dev

``` sh
pip install -e .
nbdev_export
```
