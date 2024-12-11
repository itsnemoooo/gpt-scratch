# GPT Scratch Project

## Overview
This project implements a Generative Pre-trained Transformer (GPT) model using PyTorch. It includes various components such as data loading, model architecture, and training routines. Below is a brief description of the files included in this project, along with instructions on how to set up the environment and run the code.

## File Descriptions

1. **gpt.py**
   - This file contains the main implementation of the GPT model, including the architecture, training loop, and generation methods. It handles the loading of the input data, defines the model structure, and trains the model on the Shakespeare dataset.

2. **bigram-ex.ipynb**
   - A Jupyter notebook that demonstrates a simple bigram language model. It includes code for data preparation, model training, and generating text based on the trained model.

3. **self-attention.ipynb**
   - A Jupyter notebook that explores the self-attention mechanism in detail. It provides various implementations of self-attention, including averaging, matrix multiplication, and the use of softmax for attention weights.

4. **input.txt**
   - The text file containing the Shakespeare dataset used for training the GPT model.

5. **requirements.txt**
   - A file listing the required Python packages for the project. This is used to set up the environment.

## Installation Instructions

To run this project, follow these steps:

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd gpt-scratch
   ```

2. **Set Up a Virtual Environment (Optional but Recommended)**
   You can create a virtual environment to manage dependencies:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows use: .venv\Scripts\activate
   ```

3. **Install Required Packages**
   Install the necessary packages using pip:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Jupyter Notebooks**
   You can run the Jupyter notebooks using:
   ```bash
   jupyter notebook
   ```
   This will open a web interface where you can select and run the notebooks.

5. **Run the GPT Model**
   To train the GPT model, you can execute the `gpt.py` script:
   ```bash
   python gpt.py
   ```

## Usage
- After running the notebooks, you can experiment with the models by modifying the code and re-running the cells.
- For the `gpt.py` script, you can adjust hyperparameters at the top of the file to see how they affect training and generation.

## Notes
- Ensure you have a compatible version of Python (3.7 or higher) and PyTorch installed.
- The project is designed for educational purposes and may require further optimization for production use.

Feel free to explore the files and modify the code to better understand the workings of the GPT model and self-attention mechanisms!