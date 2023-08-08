# LicSBAS_remove_Bad_images


You can employ this code to sequentially open images and subsequently exclude each of them for the remaining steps of LicSBAS processing. Execute this code within a Jupyter Notebook environment.

## Overview
This script is designed to process and manage interferograms. It displays images, allows the user to retain or move the interferograms to a specified directory, and offers navigation options through the images.

## Written by
Mohammadhoosein Mohamamdnia  
Email: mhmnia@connect.hku.hk  
Date: 7-20-2023

## Prerequisites
The script requires the following libraries:

- `os`
- `shutil`
- `ipywidgets`
- `IPython`
- `PIL` (Pillow)

Please ensure that you have these libraries installed in your Python environment before running the script.

## Installation
1. Clone the repository to your local machine.
2. Navigate to the directory containing the script.
3. Install the necessary libraries using the following commands:
   ```bash
   pip install ipywidgets
   pip install pillow

    Make sure you have the required directories and files as specified in the script (base_dir, bad_ifgs_dir, etc.).

Usage

    Open a Jupyter Notebook or IPython environment.
    Import the script or copy and paste the code into a notebook cell.
    Run the script.

The script will display the interferogram images and allow you to navigate through them, retain them, or move them to a specified directory as per your selection.


Feel free to modify or expand this template to suit your project's needs.
