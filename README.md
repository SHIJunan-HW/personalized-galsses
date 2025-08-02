# Personalized Glasses Try-On

This repository contains code and resources for a personalized glasses virtual try-on project, based on the work from GlassesGAN.

## Project Overview

This project aims to provide a tool for virtually trying on different glasses styles. It leverages the GlassesGAN model for realistic image generation and manipulation.

## Source Code & Attribution

The core code for the glasses try-on functionality is adapted from the excellent work by pleshro:
*   **Original Repository:** [https://github.com/pleshro/GlassesGAN_release#](https://github.com/pleshro/GlassesGAN_release#)
*   Please refer to the original repository for detailed methodology, model architecture, and specific instructions related to the core GAN implementation.


## Pre-trained Models

The pre-trained model files required to run the application can be downloaded from Google Drive:

*   **Download Link:** [https://drive.google.com/open?id=1N8SNUuk3zr8CoZo1Mc1q_JnJOtbG7nDe&usp=drive_fs](https://drive.google.com/open?id=1N8SNUuk3zr8CoZo1Mc1q_JnJOtbG7nDe&usp=drive_fs)

**Note:** Download the necessary `.pt`, `.pth`, or other model files from this link and place them in the correct locations as specified by the code.

## Usage

1.  **Set up the environment:** Install the required Python packages.
2.  **Download models:** Download the pre-trained models from the Google Drive link above and place them in the designated folders.
3.  **Run the Demo:** Launch the Jupyter notebook `Glasses_Try_on_App_demo_V2.ipynb` (or the relevant script) to interact with the virtual try-on application.
    *   You can typically upload your own face image.
    *   Select a glasses style from the provided CSV (`glasses_styles.csv`) or input a style code.
    *   The model will generate an image of you wearing the selected glasses.

## License

The license for the core GlassesGAN code should be checked in the original repository ([https://github.com/pleshro/GlassesGAN_release](https://github.com/pleshro/GlassesGAN_release)). Any additional code or modifications in this repository are provided under the terms specified in the `LICENSE` file (if present).
<img width="884" height="697" alt="interface" src="https://github.com/user-attachments/assets/6a727f59-a1d4-45ac-a9dd-2260acecf382" />
