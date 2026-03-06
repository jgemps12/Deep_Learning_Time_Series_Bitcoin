# Time-Series Data and Predicting Cryptocurrency Prices using Deep Learning

## About this Project:
This project uses **Recurrent Neural Networks (RNNs)** to predict closing prices for Bitcoin *one week* into the future. Multiple RNN configurations are tested to determine the best possible model for solving this 
***time-series*** problem. Afterwards, the model becomes supplemented with several deep learning techniques relating to **augmentation**, **regularization**, and **other model architectures**.

Model performance is evaluated by use of scoring metrics, such as **loss** and **Mean Absolute Error (MAE)**. These metrics are used to determine which techniques help the model predict Bitcoin prices best.

## Dataset:
This project uses the ***BTC_USD*** dataset from Yahoo! Finance. The time-series data used from the dataset ranges between 5/3/2019 and 5/9/2024. 

To use the time-series data from that specific time period, you can access all the necessary files from the **BTC_USD** folder inside this repository. These files need to be downloaded onto Google
Drive for them to work on the Google Colab notebook listed below. To run these files:

> 1.) Go to the ***BTC_USD*** directory in this repository. Make sure you download *all four* .csv files onto your computer.

> 2.) Go to the ***My Drive*** page on Google Drive. Create a folder called **BTC_USD**.

> 3.) Inside the **BTC_USD** folder, upload *all four* .csv files onto Google Drive. The dataset files should now cooperate with the Google Colab notebook.

## Source Information

1.) **Jupyter Lab** notebook
  - A Jupyter ***source file*** (.ipynb) can be found in this **repository**. This file is meant to run on your machine.

2.) **Google Colab** notebook (same as Jupyter Lab notebook)
  - An ***HTML*** version can be found in this **repository**. This file is strictly meant for reading the code.
  - An ***online***, interactive version can be viewed by clicking this **link**:
    - https://colab.research.google.com/drive/1vAAGhfo5H1Ijg6FHuKbH15rGTVB2ilBB?usp=sharing
    
3.) **Overleaf Report**
  - A ***PDF*** version can be found in this **repository**. 
  - An ***online***, read-only version can be viewed by clicking this **link**:
    - https://www.overleaf.com/read/gxyhtddsvzcp#613bfa
