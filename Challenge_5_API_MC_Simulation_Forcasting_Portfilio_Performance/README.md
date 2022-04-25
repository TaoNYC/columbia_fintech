# Portfolio Forcast using API and Monte Carlo Simulation  

This is a Python application allowing users to do financial planning by calculating his retirement portfolio including crypto, stocks & bond and also use simulation tools to forcast future performance of the portfolio (10 years & 30 years). 

 The application works by extracting crypo/stock/bond prices by using Alpaca API to evaluate current portfilio valie. Then use monte carlo similuation to forcast the stock/bond portfolio valie in 10 years /30 years by applying past 3 years performance (SPY & AGG with different percentage)
 

 
---

## Technologies

This project leverages python 3.7 +, pandas, numpy, pathlib


---

## Installation Guide

Before running the application, first make sure below libaries are installed

```python
  pip install pandas
  pip install numpy

```
Alerternatively you can simply just install requirement file included in this folder
```python
  pip install -r requirement.txt

```

---

## Usage

Step 1: run financial_planning_tools.ipynb
```python
python financial_planning_tools.ipynb
```
Step 2: Evaluate the Cryptocurrency Wallet by Using the Requests Library0

<img width="1010" alt="image" src="https://user-images.githubusercontent.com/99616004/165002782-7aace1a6-680e-4015-bc08-7675ba5d99da.png">

Step 3: Evaluate the Stock and Bond Holdings by Using the Alpaca SDK

<img width="1003" alt="image" src="https://user-images.githubusercontent.com/99616004/165002855-5935e09e-e544-49ea-aa5c-2c9fbaebf6f1.png">


Step 4: Plot the total value of the member's portfolio (crypto and stock/bond) in a pie chart

<img width="565" alt="image" src="https://user-images.githubusercontent.com/99616004/165002907-e73b3158-d359-4391-b64c-0f32966ca9d5.png">

Step 5: run and Visualize the 30-year Monte Carlo simulation on Stock/bond 

<img width="578" alt="image" src="https://user-images.githubusercontent.com/99616004/165002961-3aaa62a8-8d19-48df-8e11-c06a6186868a.png">

Step 6: Visualize the probability distribution of the 30-year Monte Carlo simulation 

<img width="434" alt="image" src="https://user-images.githubusercontent.com/99616004/165002999-f7617920-c477-499a-8d1f-9073f443898a.png">

Step 6: repeat same process of step 5 & 6 for 10 Year 


Conclution:  

looking at simulation results, even 80% in stocks & 20% in bond, the lower 95% confidence internal is only $70K, which is not likely to be enough to retire in 10 years 



## Contributors

Brought to you by TaoNYC.
connorchen7@gmail.com

---

## License

Columbia Fintech Coding Bootcamp
