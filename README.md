# Investment-and-Trading-Capstone-Project


## Table of Contents:
1. [ Project Overview.](#prov)
2. [Installations.](#instal)
3. [Files Descriptions.](#fd)
4. [4444.](#me)
5. [Instructions.](#instr)
6. [666.](#scr)
7. [Licensing, Authors, Acknowledgements.](#li)


<a name="prov"></a>
## Project Overview:

In this project I have built a stock price predictor that takes daily trading data over a certain date range as input, and outputs projected estimates for given query dates. 

<a name="instal"></a>
## Installations:

to get the stock market information you need to pip install get-all-tickers

`pip install get-all-tickers`

I did my project on the 3.6.3 version of Python and used the following libraries:

sys<br />
sqlchemy<br />
sqlite3<br />
pandas<br />
numpy<br />

sklearn<br />
pickle<br />
flask<br />

plotly<br />



<a name="fd"></a>
## Files Descriptions:

-- EFWUE<br />
| -- ABUZG <br />
| |--  WEFWEGF -----------------> main page of web app<br />
| |-- segfeawg----------------------> classification result page of web app<br />
|-- afgg -----------------------> Flask file that runs app<br />



<a name="me"></a>
## Model explanation:

**11111**

<a name="instr"></a>
## Instructions:

There are 3 steps to be executed to run the project:

1. Clean Data<br />
to run the script cleaning data you need to go to the project directory and run the following command:
```
python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db
```
2. Run ML pipeline that trains classifier and saves it<br />
for that to be done run this command from the project directory:
```
python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl
```
3. Run web app<br />
for that run the following command from app's directory
```
python run.py
```
Go to http://0.0.0.0:3001/

<a name="scr"></a>

zaewtvrliwetzi vtetoöi

<a name="li"></a>
## Licensing, Authors, Acknowledgements:

I would like to give a credit to:
@Udacity
Ran Aroussi for his codes to get data from Yahoo Finance https://github.com/ranaroussi/yfinance in a comfort way.
https://github.com/shilewenuw/get_all_tickers
https://quant.stackexchange.com/questions/26162/where-can-i-get-a-list-of-all-yahoo-finance-stocks-symbols
https://github.com/arseniyturin/Capstone-Project
