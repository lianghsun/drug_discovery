# Prerequisites
- Install the required packages by running the following command:
  ```bash
  pip install -r requirements.txt
  ```

# Dataset
- Download the SMILES dataset from [Kaggle ZINC 250k](https://www.kaggle.com/datasets/lianghsunhuang/zinc-250k). Change the file extension to `.smi` and remove the header row.
- Place the prepared `.smi` file in the `datasets` folder.

# Preprocessing
- Use `preprocess.ipynb` and run the notebook to preprocess the `.smi` file and obtain the tokenization mapping table.

# Running the Main Script
~~We have provided a token file for this project, so you can skip the `Load Training Data` section and proceed with running the rest of the code.~~

 > Note: Due to the nature of Variational Autoencoders (VAE), there might be instances where new compounds are not generated (sampling problem). If this happens, please run the code multiple times to obtain a valid compound.

# License
This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.
