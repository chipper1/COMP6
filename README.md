## COmprehensive Machine-learning Potential (COMP6) Benchmark Suite
This repository contains the COMP6 benchmark for evaluating the extensibility of machine-learning based molecular potentials.

##### If you use the COMP6 benchmark please cite this paper: 

### Active learning-based (ANI-1x):
Justin S. Smith, Ben Nebgen, Nicholas Lubbers, Olexandr Isayev, Adrian E. Roitberg. *Less is more: sampling chemical space with active learning*. The Journal of Chemical Physics 148, 241733 (2018), (https://aip.scitation.org/doi/abs/10.1063/1.5023802)

## Usage
Please read the README.md in the repository linked below for instructions on how to extract the COMP6 HDF5 (extention \*.h5) files. 
https://github.com/isayev/ANI1_dataset

The following paper contains a description of the file format:
https://www.nature.com/articles/sdata2017193

## COMP6 Benchmark Results:
#### These results represent the errors (MAE/RMSE) over the entire benchmark using a single ML potential (column 1). Please read https://aip.scitation.org/doi/abs/10.1063/1.5023802 Section IID for a detailed description of the error metrics.
#### Please contact Justin S. Smith at jussmith48@gmail.com if you'd like to add your results from the COMP6 benchmark.
### Complete COMP6 benchmark results:
|   Potential        |     Energy       | Relative Energy  |        Force     |
| ------------------ | ---------------- | ---------------- | ---------------- |
| ANI-1x<sup>1</sup> |  1.93/3.37       |    1.85/2.95     |      3.09/5.29   |
| ANI-1<sup>1</sup>  |  5.01/16.9      |    3.01/6.97     |      3.70/7.13   |

Units: kcal/mol and kcal/mol/A (errors are NOT per atom)
Error key: MAE/RMSE

##### 1) https://aip.scitation.org/doi/abs/10.1063/1.5023802

## Related work

### ANAKIN-ME ML Potential Method:
Justin S. Smith, Olexandr Isayev, Adrian E. Roitberg. *ANI-1: An extensible neural network potential with DFT accuracy at force field computational cost*. Chemical Science, 2017, DOI: [10.1039/C6SC05720A](http://pubs.rsc.org/en/content/articlelanding/2017/sc/c6sc05720a)

### Original ANI-1 data:
Justin S. Smith, Olexandr Isayev, Adrian E. Roitberg. ANI-1, A data set of 20 million calculated off-equilibrium conformations for organic molecules. Scientific Data, 4, Article number: 170193, DOI: 10.1038/sdata.2017.193 https://www.nature.com/articles/sdata2017193

### Active learning and transfer learning-based (ANI-1ccx):
Justin S. Smith, Benjamin T. Nebgen, Roman Zubatyuk, Nicholas Lubbers, Christian Devereux, Kipton Barros, Sergei Tretiak, Olexandr Isayev, Adrian Roitberg. Outsmarting Quantum Chemistry Through Transfer Learning. ChemRxiv, 2018, DOI: [https://doi.org/10.26434/chemrxiv.6744440.v1]
