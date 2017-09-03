# EVmutation
Mutation effects predicted from sequence co-variation

## Please note:

*This package has been superseded by the [EVcouplings package](https://github.com/debbiemarkslab/EVcouplings), which covers the full computational pipeline including alignment generation, 3D structure prediction, and more. All functionality present in the EVmutation package is also available through EVcouplings; the repository here will only be kept as an archive and not be updated in the future.*

## Usage

### EVmutation

Python code to compute mutation effects from a graphical model inferred using plmc. This code requires an up-to-date Python 3 installation, and the following packages (we recommend using the latest [Anaconda Python 3 distribution](https://www.continuum.io) which includes all of these packages by default):
* numpy
* scipy
* pandas
* numba

### plmc

C code to infer pairwise undirected graphical models for families of biological sequences. For installation instructions, please refer to README.md in the plmc subdirectory. This subfolder contains a copy of plmc which is developed using an independent [Github repository](http://github.com/debbiemarkslab/plmc).

### Tutorial

For a tutorial on how to infer a graphical model from a sequence alignment and how to predict the effects of mutations, please see the included Jupyter notebook [EVmutation.ipynb](https://github.com/debbiemarkslab/EVmutation/blob/master/EVmutation.ipynb). The repository also includes a static HTML export of the notebook that can be viewed without a Jupyter installation.

## Reference

If you use this code, please cite the following paper:

Hopf, T. A., Ingraham, J. B., Poelwijk, F.J., Schärfe, C.P.I., Springer, M., Sander, C., & Marks, D. S. (2016). [Mutation effects predicted from sequence co-variation](http://www.nature.com/nbt/index.html). Nature Biotechnology, *in press*.

## Author

The EVmutation module was written by [Thomas Hopf](mailto:thomas.hopf@gmail.com) in the labs of [Debora Marks](https://marks.hms.harvard.edu) and [Chris Sander](http://sanderlab.org) at Harvard Medical School. The included plmc code was written by [John Ingraham](mailto:john.ingraham@gmail.com) ([plmc repository](http://github.com/debbiemarkslab/plmc)).
