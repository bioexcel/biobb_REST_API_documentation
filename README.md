[![](https://readthedocs.org/projects/biobb-rest-api-documentation/badge/?version=latest)](https://biobb-rest-api-documentation.readthedocs.io/en/latest/?badge=latest)
[![](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/bioexcel/biobb_REST_API_documentation/master?filepath=biobb_REST_API_documentation%2Fnotebooks%2Fbiobb_REST_API_documentation.ipynb)

# BioBB REST API documentation tutorial

This tutorial explains how to execute the different endpoints of the [BioBB REST API](https://mmb.irbbarcelona.org/biobb-api). Besides, it provides the users with several functions created to make easier the connection to the REST API through a Jupyter Notebook document.

***

## Settings

### Auxiliar libraries used

* [requests](https://pypi.org/project/requests/): Requests allows you to send *organic, grass-fed* HTTP/1.1 requests, without the need for manual labor.
* [nb_conda_kernels](https://github.com/Anaconda-Platform/nb_conda_kernels): Enables a Jupyter Notebook or JupyterLab application in one conda environment to access kernels for Python, R, and other languages found in other environments.
* [nglview](http://nglviewer.org/#nglview): Jupyter/IPython widget to interactively view molecular structures and trajectories in notebooks.
* [ipywidgets](https://github.com/jupyter-widgets/ipywidgets): Interactive HTML widgets for Jupyter notebooks and the IPython kernel.
* [plotly](https://plot.ly/python/offline/): Python interactive graphing library integrated in Jupyter notebooks.

### Conda Installation and Launch

```console
git clone https://github.com/bioexcel/biobb_REST_API_documentation.git
cd biobb_REST_API_documentation
conda env create -f conda_env/environment.yml
conda activate biobb_REST_API_documentation
jupyter-nbextension enable --py --user widgetsnbextension
jupyter-nbextension enable --py --user nglview
jupyter-notebook biobb_REST_API_documentation/notebooks/biobb_REST_API_documentation.ipynb
```

***

## Tutorial

Click here to [view tutorial in Read the Docs](https://biobb-rest-api-documentation.readthedocs.io/en/latest/tutorial.html)

Click here to [execute tutorial in Binder](https://mybinder.org/v2/gh/bioexcel/biobb_REST_API_documentation/master?filepath=biobb_REST_API_documentation%2Fnotebooks%2Fbiobb_REST_API_documentation.ipynb)

***

## Version
May 2020 Release

## Copyright & Licensing
This software has been developed in the [MMB group](http://mmb.irbbarcelona.org) at the [BSC](http://www.bsc.es/) & [IRB](https://www.irbbarcelona.org/) for the [European BioExcel](http://bioexcel.eu/), funded by the European Commission (EU H2020 [823830](http://cordis.europa.eu/projects/823830), EU H2020 [675728](http://cordis.europa.eu/projects/675728)).

* (c) 2015-2020 [Barcelona Supercomputing Center](https://www.bsc.es/)
* (c) 2015-2020 [Institute for Research in Biomedicine](https://www.irbbarcelona.org/)

Licensed under the
[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0), see the file LICENSE for details.

![](https://bioexcel.eu/wp-content/uploads/2019/04/Bioexcell_logo_1080px_transp.png "Bioexcel")
