# Underwater Object Detection

Welcome to the Underwater Object Detection project! This repository is dedicated to the task of detecting and classifying underwater creatures in images. The dataset consists of 638 images, each annotated with the location of objects belonging to one of the following seven classes: 'fish', 'jellyfish', 'penguin', 'puffin', 'shark', 'starfish', and 'stingray'.

&nbsp;

## Dataset Overview

- **Classes:**
  - fish
  - jellyfish
  - penguin
  - puffin
  - shark
  - starfish
  - stingray

- **Annotation Format:**
  The dataset annotations are provided in YOLO format, allowing for easy integration with popular object detection frameworks.

- **Data Split:**
  The dataset has already been split into the following sets:
  - Training Set
  - Validation Set
  - Test Set

- **Total Images:**
  638 images are included in the dataset, providing a diverse range of underwater scenes.

&nbsp;
## Pre-Processing

### Auto-Orientation and Resize

To ensure consistency and ease of use, each image in the dataset has undergone the following pre-processing steps:

1. **Auto-Orientation:**
   The pixel data of each image has been auto-oriented, with EXIF-orientation stripping. This step helps in standardizing the orientation of images, ensuring that they are all in a consistent format.

2. **Resize to 1024x1024:**
   All images have been resized to 1024x1024 pixels. This resizing is done while maintaining the aspect ratio of the original images. This step is crucial for fitting the images within a common size, facilitating efficient training and testing of object detection models.

&nbsp;
## Getting Started

To get started with the Underwater Object Detection project, follow these steps:

1. **Clone the Repository:**
    ```
    git clone https://github.com/Ahmed-Alqershi/underwater-object-detection.git
    cd underwater-object-detection
    ```
2. **Download the Dataset:**
Download the dataset and place it in the appropriate directories (train, val, test) within the project structure.

3. **Install Dependencies:**
    ```
    pip install -r requirements.txt
    ```

4. **Explore the Code:**
Dive into the codebase to understand the implementation details, configuration files, and training scripts.

5. **Train and Evaluate Models:**
Use the provided scripts to train and evaluate object detection models on the underwater creature dataset.

&nbsp;
## Contribution Guidelines
If you wish to contribute to this project, you are welcome to do so by bug reports and feature requests.

&nbsp;
## License

`## TODO`

Feel free to reach out if you have any questions or suggestions. Happy coding! 🌊🐠🦑🦈

