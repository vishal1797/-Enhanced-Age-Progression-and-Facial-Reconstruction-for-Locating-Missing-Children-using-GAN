# Enhanced Age Progression and Facial Reconstruction for Locating Missing Children using GAN

## Project Overview

This project aims to leverage Generative Adversarial Networks (GANs) to perform age progression and facial reconstruction, providing a tool to assist in locating missing children. The system is designed to generate realistic age-progressed images and reconstruct facial features from various inputs, which can be crucial for long-term missing person cases.

## Repository Structure

The repository contains the following key files:

- `GANTest1.ipynb`: A notebook for testing the GAN model with various inputs.
- `GANTrain.ipynb`: A notebook for training the GAN model on the provided dataset.
- `age_progression_final.ipynb`: The final notebook that combines the age progression and facial reconstruction functionalities.
- `requirements.txt`: A file listing all the dependencies required to run the notebooks.

## Setup Instructions

### Prerequisites

Ensure you have Python 3.8 or later installed on your system. You will also need to install Jupyter Notebook or JupyterLab to run the `.ipynb` files.

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/Enhanced-Age-Progression-GAN.git
    cd Enhanced-Age-Progression-GAN
    ```

2. **Create a virtual environment** (optional but recommended):
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
    ```

3. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

### Running the Notebooks

1. **Start Jupyter Notebook or JupyterLab**:
    ```bash
    jupyter notebook
    # or
    jupyter lab
    ```

2. **Open and run the notebooks**:
    - Open `GANTrain.ipynb` to train the GAN model on your dataset.
    - Use `GANTest1.ipynb` to test the trained model with different inputs.
    - Finally, use `age_progression_final.ipynb` for performing the complete age progression and facial reconstruction.

## Usage

### Training the Model

1. Load your dataset into the `GANTrain.ipynb` notebook. Ensure your dataset is properly formatted and preprocessed as required by the notebook.
2. Follow the steps in the notebook to configure and train the GAN model.
3. Save the trained model for later use.

### Testing the Model

1. Open `GANTest1.ipynb`.
2. Load the trained model.
3. Input the images or data you want to test with the GAN model.
4. Run the cells to generate and visualize the output.

### Age Progression and Facial Reconstruction

1. Open `age_progression_final.ipynb`.
2. Load the trained model.
3. Follow the instructions in the notebook to input the initial images and parameters for age progression.
4. Run the notebook cells to generate age-progressed images and perform facial reconstruction.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- [Original GAN Paper](https://arxiv.org/abs/1406.2661)
- [Age Progression Techniques](https://example.com/age-progression)
- [Facial Reconstruction Methods](https://example.com/facial-reconstruction)
