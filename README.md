# ACoSDN

## Model Architecture

The overall architecture of our proposed ACoSDN:

<p align="center">
  <img src="assets/ACoSDN.pdf" width="85%">
  </p>


## Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/HiiragiUtena/MERC_ACoSDN.git
    cd ACoSDN
    ```

2.  **Create and activate a conda environment:**
    We recommend using Conda for environment management.
    ```bash
    conda create -n acosdn python=3.9 
    conda activate acosdn
    ```

3.  **Install dependencies:**
    Install the required libraries from `requirements.txt`.
    ```bash
    pip install -r requirements.txt
    ```

## Usage

### Training

To train the ACoSDN model from scratch, use the `train.py` script. You can specify the dataset and other hyperparameters.

**Train:**
```bash
python train.py --dataset iemocap --batch_size 16 --learning_rate 1e-5 --epochs 50

python train.py --dataset meld --batch_size 32 --learning_rate 1e-5 --epochs 40
```

## Acknowledgements

Special thanks to the COSMIC for sharing their codes and datasets.
