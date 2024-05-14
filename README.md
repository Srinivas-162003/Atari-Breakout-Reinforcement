## Setup Instructions

To run this code, follow these instructions:

1. **Create a new Conda environment:**

    ```bash
    conda create --name my_env python=3.10
    conda activate my_env
    ```

2. **Install required libraries:**

    ```bash
    pip install gym
    pip install gym[atari]
    pip install gym[accept-rom-license]
    pip install tensorflow
    ```

3. **For GPU support:**

    - Mention Python 3.10 when creating the environment.
    - Install CUDA toolkit and cuDNN.
    - Install TensorFlow less than version 2.11.

    ```bash
    conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1.0
    python -m pip install "tensorflow<2.11"
    ```

## Running the Code

Once the environment is set up, you can run the code using your preferred Python IDE or command line interface.

