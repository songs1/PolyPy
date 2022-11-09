# PolyPy3
Polymer and Molecular Property Prediction using Machine Learning
Last updated: 11/8/2022

Samuel W. Song
Undergraduate research project (UROP) with the Computational Design and Fabrication Group (CDFG)
Computer Science and Artificial Intelligence Laboratory (CSAIL) at the Massachusetts Institute of Technology (MIT) 

Databases:
- CROW PolymerDatabase (Glass Transition Temperature)
- Azfal-Bicerano (Glass Transition Temperature)
- Freesolv (Free Energy of Hydration)
- Lipophilicity (Log D7.4)
- Log-Permeability data from IBM (individual x6 and combined Bayesian predicted values)
- Additional datasets: HOPV, clintox, DILI, PTC; (note these last 3 are binary classification, not regression) 

Benchmarks implemented:
- Multi-Layer Perceptron (Keras/TensorFlow, PyTorch)
- 1D Convolutional Neural Network (Keras/TensorFlow)
- Random Forest (Sklearn)

Recommended improvements:
- Refactor how datasets are imported. Create an object for datasets with standard attributes (smiles, fp_counts, fp_bits, labels) and methods (create and plot test-split indices)
- Reorganize files into folders (data, test_splits, exec, exec/results). Leave "PolyPy3_load_data" and "PolyPy3_benchmarks" in the main directory since these two files contain all of the proper code
