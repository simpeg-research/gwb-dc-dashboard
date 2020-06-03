**| [usage](#usage) | [running the notebooks](#running-the-notebooks) | [issues](#issues) | [license](#license)|**

# gwb-dc-dashboard

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/simpeg-research/gwb-dc-dashboard/master)
[![Build Status](https://travis-ci.org/simpeg-research/gwb-dc-dashboard.svg?branch=master)](https://travis-ci.org/simpeg-research/gwb-dc-dashboard)
[![License](https://img.shields.io/github/license/simpeg-research/gwb-dc-dashboard.svg)](https://github.com/simpeg-research/gwb-dc-dashboard/blob/master/LICENSE)
[![SimPEG](https://img.shields.io/badge/powered%20by-SimPEG-blue.svg)](http://simpeg.xyz)

Dashboard example for inverting 1D DC resistivity data

This example runs a DC resistivity forward simulation for a 1D layered earth model that can have up to 5 layers. 

![currents3layermodel](currents3layermodel.png)

You can also run the example as a [voila dashboard](https://github.com/QuantStack/voila) using the below link

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/lheagy/gwb-dc-dashboard/master?urlpath=voila%2Frender%2FDC-Forward-Simulation.ipynb)

## Usage

Dependencies are specified in [requirements.txt](/requirements.txt)

```
pip install -r requirements.txt
```

To run the notebooks locally, you will need to have python installed,
preferably through [anaconda](https://www.anaconda.com/download/) .

You can then clone this repository. From a command line, run

```
git clone https://github.com/simpeg-research/gwb-dc-dashboard.git
```

Then `cd` into the `gwb-dc-dashboard` directory:

```
cd heagy-2018-AEM
```

To setup your software environment, we recommend you use the provided conda environment

```
conda env create -f environment.yml
conda activate gwb-dc
```


alternatively, you can install dependencies through pypi

```
pip install -r requirements.txt
```

You can then launch Jupyter

```
jupyter notebook
```

Jupyter will then launch in your web-browser.

## Running the notebooks

Each cell of code can be run with `shift + enter` or you can run the entire notebook by selecting `cell`, `Run All` in the toolbar.

<img src="https://em.geosci.xyz/_images/run_all_cells.png" width=80% align="middle">

For more information on running Jupyter notebooks, see the [Jupyter Documentation](https://jupyter.readthedocs.io/en/latest/)

## Issues

Please [make an issue](https://github.com/simpeg-research/gwb-dc-dashboard/issues) if you encounter any problems while trying to run the notebooks.


## License
These notebooks are licensed under the [BSD3 License](/LICENSE) which allows academic and commercial re-use and adaptation of this work.

