# Single-image_HDR_reconstruction
Single-image HDR reconstruction by dual learning the camera imaging process

## Introduction
The paper addresses the challenge of reconstructing HDR images from single LDR images. The authors propose a dual learning framework (DuHDR) that simultaneously learns the forward and reverse camera imaging processes to address issues related to many-to-many mapping, image quality, and the lack of paired LDR-HDR training images.

## Key Contributions
1. **Dual Learning Framework**: Simultaneously learns the forward (LDR to HDR) and reverse (HDR to LDR) camera imaging processes.
2. **Attention Mechanism**: Addresses perceptual quality issues by adjusting for changes in contrast and saturation.
3. **Semi-supervised Training**: Uses unpaired LDR images to increase training data diversity and enhance model generalization.

## Practical Applications
- Enhancing LDR images to obtain high-quality HDR images.
- Mapping HDR images to LDR for compatibility with LDR displays.
- Converting HDR video to LDR for easier encoding and then restoring HDR from LDR for playback.

## Python Code
The Python code in this repository simulates the process of reconstructing HDR images from LDR images using a dual learning framework.

### Data Preprocessing
```python
def load_data():
    # This function should load and preprocess the dataset
    # For simplicity, we are using dummy data
    X_train = np.random.rand(100, 128, 128, 3)
    Y_train = np.random.rand(100, 128, 128, 3)
    return X_train, Y_train


To understand how the project works, please watch the video below:
https://drive.google.com/drive/folders/1YU1DuezjzxzlGufcMelF5Cv__-hpYAy9?usp=drive_link
To run the files more easily and effectively, please execute them in the following order:
Single-image HDR reconstruction by dual learning
proposal and article use in this project https://drive.google.com/file/d/1Qti306fL4xdy2M426523CajrfeFA_QL1/view?usp=drive_link
If you have any questions or encounter issues with the implementation of the code, feel free to send an email to the following address:
fatememajidi1373@gmail.com
