# HPBDAIS_final_project
fMRI Parcellation and Analysis System

## Overview
This project aims to develop a system for simulating different fMRI parcellations and analyzing them using various strategies. The goal is to explore the performance of different packages, such as sklearn and cuML, on both CPU and GPU platforms. Additionally, the project will investigate methods like parallelization to enhance the efficiency of the time-consuming analysis process.

## Environment Setup

1. **Install Conda:**

   - Follow the official Conda installation instructions for your operating system.

2. **Create the Conda environment:**

   - Run the following command to create the environment:
     ```
     conda env create -f environment.yml
     ```

3. **Activate the Conda environment:**

   - Activate the Conda environment using the following command:
     - On Linux and macOS:
       ```
       conda activate myenv
       ```
     - On Windows:
       ```
       activate myenv
       ```

4. **Install additional packages using pip:**

   - Run the following command to install additional packages using pip:
     ```
     pip install -r requirements.txt
     ```

