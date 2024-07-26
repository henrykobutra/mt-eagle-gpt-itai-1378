# 🦅 EagleGPT's Object Detection Adventure 🐾

Welcome to the **EagleGPT's Object Detection Adventure**! This project is all about enhancing an object detection model using the Oxford-IIIT Pet Dataset. Get ready to dive into the world of computer vision and machine learning with a sprinkle of fun! 🎉

## Table of Contents

- [Project Overview](#project-overview)
- [Setup Instructions](#setup-instructions)
- [Notebook Walkthrough](#notebook-walkthrough)
- [Results](#results)
- [Contributors](#contributors)

## Project Overview

In this project, we embark on a journey to enhance an object detection model. Our trusty dataset is the **Oxford-IIIT Pet Dataset**, which is packed with images of adorable pets. The steps we follow include:

1. **Dataset Loading and Preparation** 🐶
2. **Model Architecture Setup** 🏗️
3. **Training** 🏋️
4. **Evaluation** 📊
5. **Fine-Tuning** 🔧
6. **Deployment with Custom Image Testing** 📸

## Setup Instructions

To get started with this project, follow these steps:

1. **Clone the Repository**:

    ```bash

    git clone https://github.com/henrykobutra/mt-eagle-gpt-itai-1378.git
    cd mt-eagle-gpt-itai-1378

    ```

2. **Install Dependencies**:
    Make sure you have Python 3.x installed. Then, install the required libraries:

    ```bash
    pip install tensorflow tensorflow-datasets matplotlib numpy
    ```

3. **Run the Notebook**:
    Open the notebook in Jupyter or any compatible environment:

    ```bash
    jupyter notebook MT_Varit_Kobutra_EagleGPT_ITAI_1378.ipynb
    ```

## Notebook Walkthrough

Here's a quick tour of what you'll find in the notebook:

### Initial Setup

We kick things off by importing essential libraries like TensorFlow, TensorFlow Datasets, Matplotlib, and NumPy. These are our tools for data manipulation, model building, and visualization.

### Helper Function to Visualize Data

We define a nifty helper function, `show_samples`, to visualize dataset samples with their corresponding class names. This helps us get a feel for the data we're working with.

### Dataset Selection and Preparation

We load the Oxford-IIIT Pet Dataset and extract class names for further use in visualization and labeling. We also display a few sample images to understand the dataset's structure.

### Model Building and Training

We set up our model architecture, train it on the dataset, and evaluate its performance. Fine-tuning is done to enhance the model's accuracy.

### Custom Image Testing

Finally, we test our model with custom images to see how well it performs in real-world scenarios.

## Results

By the end of this project, you'll have a robust object detection model capable of identifying various pet breeds with impressive accuracy. 🏆

## Contributors

This project was brought to life by the brilliant minds of the **EagleGPT Team**. Special thanks to our instructor and classmates for their support and feedback.

---

Happy coding and may your models be ever accurate! 🚀
