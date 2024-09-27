

# Hand Gesture Recognition Model - Task 4

## Overview
This project is part of Task 4 of my internship at Prodigy Infotech. The aim is to develop a Hand Gesture Recognition Model using the LeapGestRecog dataset, enabling intuitive human-computer interaction and gesture-based control systems.

## Project Details
- **Dataset:** [LeapGestRecog](https://www.kaggle.com/gti-upm/leapgestrecog) from Kaggle
- **Goal:** Classify different hand gestures to facilitate gesture-based controls and interactions.
- **Model:** Custom architecture designed to classify hand gestures effectively.

## Table of Contents
 [Usage](#usage)
 [Model Architecture](#model-architecture)
 [Contributors](#contributors)
 [License](#license)



## Usage
1. **Load the Model:**
    - To load the pre-trained model and test it on images, run:
    ```bash
    python load_and_test_model.py
    ```
2. **Test on New Images:**
    - Place your test images in the `test_images` folder and run the script to get predictions:
    ```bash
    python predict_gestures.py --image test_images/your_image.png
    ```

## Model Architecture
The model consists of:
- **Input Layer:** Grayscale images of size 32x32 pixels.
- **Hidden Layers:** A series of layers designed to extract and learn features of hand gestures.
- **Output Layer:** 10 classes corresponding to different hand gestures.


## Contributors
- **Saleel**, Machine Learning Intern at Prodigy Infotech

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details.

