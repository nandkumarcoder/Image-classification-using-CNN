# Image Classification Using CNN

A deep learning project for classifying images of cats and dogs using Convolutional Neural Networks (CNNs). This project uses a dataset of labeled images to train a model that can predict whether an image contains a cat or a dog.

## Features

- **Binary Classification**: Classifies images into two categories: cats and dogs.
- **Customizable Parameters**: Easily adjust dataset size, image size, and train-test split ratio.
- **Scalable**: Designed to handle large datasets.

## File Structure

- `constants.py`: Contains constants and configurations for the project, such as dataset paths, labels, and image size.
- Other files (e.g., training scripts, model definition) should be added as needed.

## Constants Overview

- `TRAIN_DIR`: Path to the training dataset.
- `TEST_DIR`: Path to the testing dataset.
- `CAT_LBL` and `DOG_LBL`: Numeric labels for cats and dogs.
- `LABEL_MAP`: A dictionary mapping labels to their numeric values.
- `DATA_SIZE`: Total number of images to use from the dataset.
- `IMG_SIZE`: Size to which all images will be resized (e.g., 110x110).
- `SPLIT_RATIO`: Ratio for splitting the dataset into training and validation sets.

## Prerequisites

- Python 3.x installed on your system.
- Required Python libraries:
  - `tensorflow` or `keras`
  - `numpy`
  - `opencv-python` (for image preprocessing)
  - `matplotlib` (for visualizations)

## Dataset

- The dataset should be organized as follows:
  ```
  train/
      cat.1.jpg
      cat.2.jpg
      ...
      dog.1.jpg
      dog.2.jpg
      ...
  test1/
      test1.jpg
      test2.jpg
      ...
  ```
- Update the `TRAIN_DIR` and `TEST_DIR` paths in `constants.py` to point to your dataset.

## How to Run

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd Image-classification-using-CNN
   ```
3. Install the required libraries:
   ```bash
   pip install tensorflow numpy opencv-python matplotlib
   ```
4. Run the training script (to be implemented):
   ```bash
   python train.py
   ```
5. Evaluate the model on the test dataset (to be implemented):
   ```bash
   python evaluate.py
   ```

## Customization

- Modify `constants.py` to adjust the dataset size, image size, or train-test split ratio.
- Add or update scripts for training, evaluation, and preprocessing as needed.

## Example

### Input:
- An image of a cat or a dog.



## License

This project is licensed under the MIT License.

## Acknowledgments

- Inspired by common image classification tasks in deep learning.
- Dataset sourced from publicly available cat and dog image datasets.
