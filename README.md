# Quantum-Classical-Hybrid-Model-for-MNIST-Classification
This project uses a Quantum Neural Network (QNN) with TorchQuantum
 to classify MNIST digits (3 vs 6). It demonstrates how quantum layers can be combined with classical preprocessing for image recognition.

Setup:
Dataset: MNIST (digits 3 & 6)
Batch size: 256
Optimizer: Adam (lr=5e-3)
Device: GPU (T4 Colab)
Epochs: 100

Results:
Validation Accuracy: 88.3%
Test Accuracy: 86.7%
Loss decreased steadily over training.

Run:
Open in Google Colab
Enable GPU (T4)
Run notebook cells

Conclusion:
QNN achieved ~87% accuracy, showing the promise of quantum-classical hybrid models for simple classification tasks.
