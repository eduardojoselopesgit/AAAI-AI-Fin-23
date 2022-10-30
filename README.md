#  "Short-term prediction for Ethereum with Deep Neural Networks"

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Folders](#folders)
* [Setup](#setup)
* [Contact](#Contact)

## General info
Code Repository and general info for AAAI-AI-Fin'23 paper. The main contribution of this research is to compare state-of-the-art deep learning architectures to predict Ethereum cryptocurrency close price on a time constrained scenario against an ARIMA model.
	
## Technologies
Project is created with:


Software
* System: Windows Version 10.0.19041
* Anaconda Navigator 2.1.1
* Jupyter notebook server version 6.4.6
* Python 3.7.11 (default, Jul 27 2021, 09:42:29) [MSC v.1916 64 bit (AMD64)]
* IPython 7.31.1

Hardware
* Processor: Intel64 Family 6 Model 165 Stepping 5, GenuineIntel
* Physical cores: 10  - Total cores: 20
* Max Frequency: 3696Mhz  - Current Frequency: 3696Mhz
* Total memory (GB):32
* GPU Information:  NVIDIA GeForce RTX 3090 - Total memory: 24576.0MB

Main packages
* psutil version 5.8.0
* GPUtil version 1.4.0
* platform version 1.0.8
* numpy version 1.21.5
* pandas version 1.3.4
* torch version 1.10.2
* logging version 0.5.1.2
* darts (u8darts) version 0.17.1

8v0_BTC-EPOCHS_100-48-1-16-TFT.ipynb

## Folders
* /model: .ipynb files used for model calculation. Filename convention: AvB_C-EPOCHS_D-E-F-G-H.ipynb, where:
* A anb B: code versioning.
* C: cryptocurrency considered (ETH = ethereum).
* D: number of epochs.
* E: not used.
* F: not used.
* G: batch size.
* H: deep learning model.
* /data: .csv file with Ethereum (ETH) timeseries information.
* /results: spreadsheet containing model results for different models and random seeds considered on model calculation.
	
## Setup
To run this project, remember::

```
1. Change the folder destination on the .ipynb files for the .csv file containing ETH timeseries information.

```

## Contact
Created by eduardo.lopes@me.com - feel free to contact me!

