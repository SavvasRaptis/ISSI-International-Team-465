# ISSI International Team 465

 Foreshocks Across The Heliosphere: System Specific Or Universal Physical Processes? ISSI Team led by H. Hietala (UK) & F. Plaschke (AT)

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

## Getting Started

[Read full proposal here](https://www.issibern.ch/teams/heliosysspec/wp-content/uploads/2020/03/Hietala_ISSI_2019_International_Team_proposal_final.pdf)

[![IMAGE ALT TEXT](http://img.youtube.com/vi/WT1oMLPgR2s/0.jpg)](http://www.youtube.com/watch?v=WT1oMLPgR2s "Do all the planets sound different?")

### Prerequisites (Windows Setup)

For the Python scripts you need to install anaconda with [jupyter](https://jupyter.org/install) and some other libraries. To do so, install [anaconda](https://docs.anaconda.com/anaconda/install/windows/) and run Anaconda Prompt Terminal. From there create an environment and update the packages via the following code:

```concole
conda create -n ISSI_465 spyder matplotlib seaborn scikit-learn pandas
conda activate ISSI_465
conda install -c conda-forge notebook
conda install -c conda-forge jupyterlab
```

Furthermore, for the usage of the examples in the notebook folder, two more packages are needed.  Python library that allows the usage of MATLAB kernel in jupyter notebooks available here: [link](https://am111.readthedocs.io/en/latest/jmatlab_install.html)


Then we also use the irfu-matlab package available at is available at [irfu](https://github.com/irfu/irfu-matlab). After installing it one can simply add the library to MATLAB's path and run:

```matlab
irfu
```
## Authors

* [![Savvas Raptis: 0000-0002-4381-3197](https://img.shields.io/badge/Savvas%20Raptis-0000--0002--4381--3197-green?style=flat&logo=orcid)](https://orcid.org/0000-0002-4381-3197)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
This code was used in the following publications:
- [![Publication: Published](https://img.shields.io/badge/Publication-Published-green?style=flat&logo=openaccess)](https://www.issibern.ch/teams/heliosysspec/index.php/publications/)
