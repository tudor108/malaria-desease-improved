This project leverages cutting-edge deep learning techniques to improve malaria diagnosis from cell images. It integrates various components designed for accuracy enhancement, model robustness, and streamlined experimentation. Key aspects include:

Dataset Augmentation: Advanced augmentations (flipping, brightness, and hue adjustments) boost the model's ability to generalize, reducing overfitting.
Feature Extraction: ResNet50 is used as a pre-trained backbone for transfer learning, fine-tuned for malaria diagnosis.
Custom Architectures: A sequential model and a custom subclassed architecture demonstrate flexible approaches to experimentation.
Comprehensive Metrics: Metrics such as precision, recall, F1 score, and AUC ensure a complete performance evaluation.
Callbacks: Learning rate scheduling, early stopping, and model checkpointing mitigate overfitting and optimize training efficiency.
Visualization: Confusion matrices and ROC-AUC plots provide insights into model behavior.
MLOps Integration: Tools like Weights & Biases support experiment tracking, hyperparameter tuning, and performance logging.
This framework achieves robust malaria classification while maintaining scalability and modularity, offering potential improvements in diagnostic tools.
