Developed a hybrid deep learning pipeline to classify diabetic retinopathy stages using fundus (retinal) images.

Preprocessed medical images using OpenCV and PIL, including Hough Circle Transform for retina-focused cropping and Gaussian filtering for noise reduction.

Extracted high-level features from images using a pretrained VGG16 CNN (with Keras), followed by dimensionality reduction and top-4 feature selection via ExtraTreesClassifier.

Normalized selected features for angle encoding into a 4-qubit quantum circuit using Qiskit’s ZFeatureMap.

Designed a custom Quantum Convolutional Neural Network (QCNN) architecture with parameterized convolution and pooling quantum layers using EstimatorQNN from Qiskit Machine Learning.

Integrated QNN with a PyTorch-based feedforward network, forming a hybrid model via TorchConnector.

Trained the model end-to-end using CrossEntropyLoss and Adam optimizer on a 5-class classification task, achieving competitive accuracy on test data.# Hybrid-Quantum-model-for-medical-imaging
