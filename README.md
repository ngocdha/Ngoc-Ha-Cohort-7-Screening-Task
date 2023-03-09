# Ngoc-Ha-Cohort-7-Screening-Tasks

I implemented 2 kernel SVM models to classify the iris dataset

- Model 1 uses QAOA embedding to compute the kernel
- Model 2 uses Angle embedding to compute the kernel

Training involves optimization of the data encoding scheme.

For the specific settings used (seed, number of layers, etc...), the result shows the Angle embedding outperforms QAOA embedding in accuracy and training time, while both method uses the same number of qubits.
