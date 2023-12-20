# CS209 Final Project - RNN model for stock price prediction for Nasdaq and three Vietnamese stock markets
## Prompt
1. Nasdaq stock price prediction (Nasdaq dataset)
2. Vietnam stock price prediction (Vietnam dataset)
3. Vietnam/Nasdaq trading point identification (Vietnam or Nasdaq dataset): Vietnam/Nasdaq trading point prediction. Basic questions to answer:
  - What is a good signal for buying stock of certain company?
  - What is a good signal for selling stock of certain company?
4. Vietnam/Nasdaq portfolio/risk management (Vietnam or Nasdaq dataset): Vietnam/Nasdaq portfolio/risk management. Basic questions to answer:
  - What is the list of companies to hold? What is the profit within a certain period?
  - What is the list of companies to get rid of? Why?
  - How to combine potential scores and risk scores into a portfolio to optimize investment strategy?

## Solution
I built two similar models for task 1 and task 2 which are LSTM - Long-Short Term Memory model. Regarding task 3 and 4, I chose Vietnam stock markets as it is harder to work with them than Nasdaq.
## How to use the codes?
I solved all four tasks in two seperate files using solely Google Colab:
1. [Model for Nasdaq stock market](https://colab.research.google.com/drive/1uxT2gvNAtY7AgHhBedSsm_JSXovmL1KF?usp=sharing)
2. [Model for three Vietnamese stock markets](https://colab.research.google.com/drive/19qxSElWrOir8OuK8vsRSdTmC56CgmZN7?usp=sharing)

Alternatively, you can also download either, or both, of the files in this repository.
I used Google Drive to contain and load the dataset from. Therefore, you must first upload the two folders below to your Google Drive:
1. [Nasdaq dataset](https://drive.google.com/drive/folders/1tE9fr_Keul1SRn4rZX6v7aVM4DAyeYUW?usp=sharing)
2. [Vietnamese stock dataset](https://drive.google.com/drive/folders/1A-P8OirrH2cW9YBeN7o30e1PrnmnrenO?usp=sharing)

Please note that both of the datasets are updated with the data until the end of February, 2023. 
After that, you can simply access to either of the two Google Colab links above to enter the chosen file and run it. All required library are either included or will be installed automatically, so you don't have to worry about missing libraries. If you run these files locally, then install the required libraries in the [requirements.txt](requirements.txt)
