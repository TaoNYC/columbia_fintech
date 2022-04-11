# Crypto Arbitrade 

This is a Python application allowing users to extract, plot and explore arbitrage oppertunities of crypto asset price difference between 2 exchangs: Bitstamp vs. Coinbase

 The application works by first loading 'min by min' close prices of Q1, 2018 from `bitstamp.csv` and `coinbase.csv`. After cleaning up the data, the app analyze the data and plot both data sets in one graph for visulzition purpose. Then the app chooses 3 dates to zoom in: 01/16/18, 02/24/18 & 03/26/18 for detail analyse of calculating the spread and potential profit from the arbitrage oppertunity.
 
---

## Technologies

This project leverages python 3.7 +, pandas, pathlib


---

## Installation Guide

Before running the application, first make sure below libaries are installed

```python
  pip install pandas

```
Alerternatively you can simply just install requirement file included in this folder
```python
  pip install -r requirement.txt

```

---

## Usage

Step 1: run App.py
```python
python crypto_arbitrage.py
```
Step 2: visulize 2 data sets from bitstamp and coinbase in Q1, 2018

<img width="887" alt="image" src="https://user-images.githubusercontent.com/99616004/162650865-9e18b71b-db54-40e1-b65d-43ca15e065a9.png">

Step 3: zoom in 3 dates: 01/16/18, 02/24/18 & 03/26/18 

<img width="884" alt="image" src="https://user-images.githubusercontent.com/99616004/162651193-098ed60e-5ce5-4c14-8e4d-7526346510b1.png">

<img width="887" alt="image" src="https://user-images.githubusercontent.com/99616004/162651228-f57c99f7-a2e0-45e0-8cf3-f54fc14ff893.png">

<img width="880" alt="image" src="https://user-images.githubusercontent.com/99616004/162651279-2fea90b1-7732-4ed8-b123-7a7ec5b956d8.png">



Step 4: calculate profit, for example below shows 01/16/18 (other 2 dates can be foud in Jupyter notebook)

<img width="886" alt="image" src="https://user-images.githubusercontent.com/99616004/162651488-7885ec15-d1e1-42f7-be81-7d1ff36fd5f2.png">


Conclution:  After reviewing 3 dates (early 01/16/18; middle 02/24/18 and late 03/26/18, the number of profitable trades has dropped drastically from 73 in early date, to 3 in middle date and none in late date. As a result, profit per day also dropped drastically from Early to Middle, and no profit at all in late date. 



## Contributors

Brought to you by TaoNYC.
connorchen7@gmail.com

---

## License

Columbia Fintech Coding Bootcamp
