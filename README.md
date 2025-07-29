# Cat vs Dog Classifier – CNN Approach

## Project Description

This project implements a Convolutional Neural Network (CNN) to classify images of cats and dogs using TensorFlow/Keras. The model is trained on the Cats vs Dogs dataset and optimized through tuning and regularization. 
Performance is evaluated with training and validation metrics.

---

## Model Architecture

- Multiple convolutional layers followed by max pooling
- Dropout layers to reduce overfitting
- Dense layers for classification
- Sigmoid activation for binary output
- Optimizer: RMSprop
- Loss Function: Binary Crossentropy

---

## Evaluation Metrics

- **Accuracy**
- **Loss**
- Training and validation performance tracked over epochs
- Visualizations provided for pre- and post-tuning comparison

---

## Key Results

- Initial validation accuracy: ~79%
- After tuning (dropout + learning rate): ~78%
- Final test accuracy: ~74.3%
- Training and validation loss curves show improved generalization

---

## Future Work

- Incorporate image augmentation
- Apply transfer learning with a pre-trained CNN (e.g., VGG16)
- Add early stopping and dynamic learning rate scheduling

---

## How to Run

1. Ensure the dataset is structured with subfolders for `train/cat`, `train/dog`, `validation/cat`, and `validation/dog`.
2. Open the Jupyter Notebook `deep-learning-final-project.ipynb`.
3. Run all cells sequentially to load data, train the model, and visualize results.
4. Modify parameters in the tuning section to experiment with improvements.

---

## Author

Erica Kim  
MS in Data Science, University of Colorado Boulder  
Project: Deep Learning – Cat vs Dog Classification 
