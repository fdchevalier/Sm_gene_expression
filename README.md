# *Schistosoma mansoni* stage gene expression

Gene expression table can help prioritize candidate genes by selecting only genes expressed in the stage of interest. Several RNA-seq datasets are already published for different stages. This is the list of dataset used in this project:
* Eggs from [Anderson *et al.*, 2015](https://doi.org/10.1371/journal.pntd.0004334)
* Miracidia from [Wang *et al.*, 2013](https://doi.org/10.7554/eLife.00768.001)
* Cercariae, schistosomula 3h and 24h (*in vitro* transformation) from [Protasio *et al.*, 2012](https://doi.org/10.1371/journal.pntd.0001455)
* Sporocyst 48h (*in vitro* transformation) from [Wang *et al.*, 2013](https://doi.org/10.7554/eLife.00768.001)
* Sporocyst within snails (1 and 3 days post exposure and field shedders) from [Buddenborg *et al.*, 2019](https://doi.org/10.1371/journal.pntd.0007013)
* Juveniles (single sex) (18, 21, 28 day old) from [Protasio *et al.*, 2017](https://doi.org/10.1371/journal.pntd.0005559)
* Adults (separate males and females from mix infections) [Protasio *et al.*, 2017](https://doi.org/10.1371/journal.pntd.0005559)

## Code

The code used to generate the stage-specific gene expression table is located in the Jupyter notebook.

## Prerequisites

Two dependencies must be installed before running the Jupyter notebook:
* A [conda](https://docs.conda.io/en/latest/) distribution, like [miniconda](https://docs.conda.io/en/latest/miniconda.html),
* [Jupyter Notebook](https://jupyter.readthedocs.io/en/latest/install.html) with a [bash kernel](https://github.com/takluyver/bash_kernel).

Once this is done, run the first cell of the Jupyter notebook from this repository to install a dedicated conda environment and related R packages.
