# Terrain Classification Model

This repository contains code for a terrain classification model, which is designed to classify different types of terrain using deep learning techniques.
The repository provides pretrained models for classifying different types of terrain using convolutional neural networks (CNN). The code for different models is organized in the `code` folder, while the pretrained models are stored in the `models` folder. Additionally, the dataset used for training and evaluation is available in the `dataset` folder.

## Development Environment
- **Platform:** NVidia AI Workbench
- **Base Image:** project-terrain-classification-model
- **Containerization:** Docker

## Apps
- visual studio code
- JupyterLab
- Tensorboard

## Package Managers

- apt
- pip

## Specifications
the following specificatiion can setted up in workbench 
- **Base Image:** PyTorch 2.1 Base with CUDA 12.2
- **Version:** v1.0.2
- **Operating System:** Ubuntu 22.04
- **Python Version:** Python 3
- **Package Managers:** apt, pip

## Repository Structure

- **code:** Contains implementations of various CNN models for terrain classification.
- **data:** Dataset used for training and evaluation.
- **models:** Pretrained models for terrain classification tasks.
- **.gitattributes:** Git attributes file.
- **.gitignore:** Gitignore file.
- **README.md:** This README file.
- **apt.txt:** List of apt dependencies.
- **postBuild.bash:** Script to run after the build process.
- **preBuild.bash:** Script to run before the build process.
- **requirements.txt:** List of Python dependencies.
- **variables.env:** Environment variables file.

## Usage

As the development environment is NVidia AI Workbench, all setup and containerization are handled automatically. To use the pretrained models or train new models, simply clone this repository and run the provided code scripts.


## Installation on local machine
for running and using the models and code on your local machine, do

1. Clone this repository:
   ```bash
   git clone https://github.com/ViratSrivastava/terrain-classification-model.git
2. Navigate to the cloned repository:
    ```bash
    cd terrain-classification-model
    ```
3. Build the Docker container:
    ```bash
    docker build -t terrain-classification-model .
    ```
4. Run the Docker container:
    ```bash
    docker run -it terrain-classification-model
    ```

# Contributing
Contributions to this repository are welcome! If you have suggestions, feature requests, or bug reports, please feel free to open an issue or submit a pull request.
