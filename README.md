# BYTE_RUSH_2
This is my project for byte_rush 2


# Brain Tumor Detection using CNN

This project involves detecting brain tumors from MRI images using a Convolutional Neural Network (CNN) model. The model is trained and evaluated on a Kaggle dataset and was developed using Google Colab.

## Dataset

The dataset used for this project is from Kaggle and contains MRI images divided into two categories:
- **Yes**: Brain tumor present
- **No**: Brain tumor not present
- **Pred**: This is just used for testing my model after training.

In addition, a `pred` folder was created to store images for predictions.

## Project Workflow

1. **Data Preprocessing**:
   - Images were resized and normalized to improve model performance.
   - The dataset was split into training and testing sets to ensure unbiased evaluation.

2. **Model Architecture**:
   - The CNN model was designed with multiple convolutional(3) and pooling layers to capture features.
   - Dropout layers were added to prevent overfitting.
   - The final layer uses a softmax activation for binary classification (tumor vs. no tumor).

3. **Training**:
   - The model was trained on Google Colab using GPU support(T4-nvidia) my PC not hold this much kind of work.
   - Data augmentation was applied to enhance model generalization like rotating a image little-bit and then resizing it and zooming in or out by factor of 0.2.

4. **Evaluation**:
   - The model's performance was evaluated using metrics such as accuracy, precision, recall, and F1-score.
   - Confusion matrices and loss/accuracy plots were generated for further insights.

## Requirements

To run this project, you need the following:
- Python 3.9
- Tensorflow and Keras for building the CNN model
- PIL for image processing
- numpy for data manipulation
# Video-LINK
[Youtube-video-for-my-project](https://youtu.be/vivnxwENVZ0)


Install dependencies using:

```bash
pip install tensorflow keras pillow numpy flask



