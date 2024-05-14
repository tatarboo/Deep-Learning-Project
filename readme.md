# Structure

The `original_data` folder contains the dataset provided by [Zhang, Bang, and Lee 2023](https://github.com/Lee-CBG/PiTE), along with their data processing methods. The dataset can be downloaded from their homepage.
The `our` folder houses our work.
The `model` folder is where we save the best-trained models. The `log` folder is used for storing training logs. The `data` folder holds the processed data, which is generated by `ourDataProcess.ipynb`.
`main.ipynb` is our file for training and testing.



# Quick Start

Please replace your data path in `main.ipynb`, as well as the addresses for saving models and logs to start the process. If you wish to select a specific model, set `args.nns` to either 'transformer', 'cnn', or 'lstm'.
