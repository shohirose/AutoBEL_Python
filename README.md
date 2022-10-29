# Automated Bayesian Evidential Learning for Geological UQ 

This is companion code repository for 
* [Yin, Z., Strebelle, S., and Caers, J.: Automated Monte Carlo-based quantification and updating of geological uncertainty with borehole data (AutoBEL v1.0), Geosci. Model Dev., 13, 651–672](https://www.geosci-model-dev.net/13/651/2020/gmd-13-651-2020.html)
<p> This repository contains the python code of automated BEL for geological model unceratinty quantification using well borehole data.

### Installation

Packages can be installed using pip or conda in the following procedures.

#### Using pip

On Linux or Mac:

```bash
$ python3 -m venv .venv
$ . .venv/bin/activate
$ pip install -r requirements.txt
```

On Windows:

```powershell
> python3 -m venv .venv
> .venv\Scripts\activate.ps1
> pip install -r requirements.txt
```

#### Using conda

```bash
$ conda env create --file autobel.yml
$ conda activate autobel
```

Once installed, jupyter can be started from command line with

```bash
$ jupyter lab
```

Or you can run JupyterLab using Visual Studio Code.
	
### Structure of the Auto BEL setup
<img src="source_code/img/dataset_struture.jpg" width="500" height="370">


### Runing the Auto BEL

1. Download this repository to your PC
2. Start Jupyter notebook,
3. Navigate to the downloaded AutoBEL_Python master folder, 
4. Open the jupyter notebook file [Control_Pannel.ipynb](https://github.com/sdyinzhen/AutoBEL_Python/blob/master/Control_Pannel.ipynb), and follow the steps in the notebook to run BEL. 

### Tutorial Video
For illustration, a [tutorial video](https://youtu.be/9dP1jCvMOXo) is provided. 

### NB
The current AutoBEL tutorial is for uncertainty quantification of continous models. We are still working to make the catergoricial faices model data publicly available. However, all the codes for facies model management are provided in the repository, including signed distances calculations and back transform (“signed_distance_functions.py”), mixed PCA (“dmat_4mixpca.py”). The tutorial will be updated as soon as the facies model becomes available.

### Licensing
This repository is released under the MIT License.
