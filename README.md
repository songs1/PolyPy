# PolyPy
Polymer property prediction UROP project with CDFG (MIT CSAIL)

Databases uploaded: CROW, Freesolv
Benchmarks implemented: Tao_MLP, my_MLP, 

Bugs:
- error when fingerprinting Azfal_Bicerano.csv (not uploaded here)
- GPR does not work, probably because fingerprints_bits > dataPoints; consider pruning down to 100 points?
