# Traffic Sign Detection (TSD)

This repository contains few files to explain and get an idea about how I performed the project.

## Directory Structure

- **test images and videos/**
  - This directory contains sample images and videos for testing the trained model. You can place your own test files here to see the model's performance on different inputs.
  
- **TSD.ipynb**
  - This Jupyter notebook file contains code for running and testing the YOLOv7 model on images. It includes steps for loading the model, preprocessing images, and displaying the results with detected traffic signs.
  
- **environment.yml**
  - This file contains the environment configuration for Conda. It lists all the dependencies and their versions required to run the project. You can create the environment using the command:
    ```sh
    conda env create -f environment.yml
    ```
  
- **requirements.txt**
  - This file lists all the Python packages required to run the project. You can install the dependencies using pip:
    ```sh
    pip install -r requirements.txt
    ```
  
- **test.py**
  - This script contains code for running the YOLOv7 model on images or videos. It includes functions for loading the model, processing the inputs, and displaying the detections.
  
- **train.py**
  - This script is used for training the YOLOv7 model on a custom dataset. It includes configuration settings and parameters for training the model.

## How to Use

1. **Set Up the Environment:**
   - Create a Conda environment using `environment.yml`:
     ```sh
     conda env create -f environment.yml
     ```
   - Or install the dependencies using `requirements.txt`:
     ```sh
     pip install -r requirements.txt
     ```

2. **Training the Model:**
   - To train the model on your custom dataset, update the `train.py` script with the path to your dataset and run:
     ```sh
     python train.py
     ```

3. **Testing the Model:**
   - Use the `test.py` script to run the model on images or videos. Ensure your test files are placed in the `test images and videos/` directory.
     ```sh
     python test.py
     ```

4. **Using the Jupyter Notebook:**
   - Open `TSD.ipynb` in Jupyter Notebook or JupyterLab to interactively test the model on images and visualize the results.

## Notes

- Ensure you have the necessary hardware (GPU) and CUDA installed for optimal performance.
- Update the paths in the scripts as per your directory structure and requirements.
- For detailed usage and customization, refer to the comments and documentation within each script.
