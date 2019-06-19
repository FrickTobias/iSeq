[![Build Status](https://travis-ci.org/FrickTobias/DBSpro.svg?branch=master)](https://travis-ci.org/FrickTobias/DBSpro)

# DBSpro Analysis

This pipeline analyses data sequencing data from DBSpro experiments for protein and PrEST quantification.

## Setup

First, make sure [conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/) is installed on your system.

- Clone the git repostory.

    ```
    git clone https://github.com/FrickTobias/DBSpro
    ```

- Create an environment and with required dependencies. 

    ```
    conda env create -n dbspro -f environment.yml
    ```

- Activate the environment.

    ```
    conda activate dbspro
    ```

- Move to the git folder and install dbspro into you environment.

    ```
    cd DBSpro
    pip install -e .
    ```

## Useage

Basic usage

```
bash DBSpro_automation.sh -t <threads> raw-reads.fq output-folder
```
