# Quantitative Portfolio analysis 

This is a Python application allowing users to analyze the historical returns & risk of 4 whale hedge funds and compare with SP500 regarding risk & return. 

 The application works by first loading from `whales_nav.csv`. After cleaning up the data which was then loaded into pandas datafrme to calculate daily / yearly returns, volatility and sharp ratio (risk adjusted return). Rolling windows were applied to smooth out the results. Finally, the application choose 2 funds to calculate their covariance vs SP500 (Beta) and plot out the results so that investors can have better understanding on riks & return via visulaizion
 

 
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

Step 1: run risk_return_analysis.ipynb
```python
python risk_return_analysis.ipynb
```
Step 2: load data, calculate and Plot the daily & cumulative returns data of the 4 funds and the S&P 500

<img width="892" alt="image" src="https://user-images.githubusercontent.com/99616004/163736789-aa68aa07-4807-4c93-b021-a5deb7a4cacd.png">

<img width="871" alt="image" src="https://user-images.githubusercontent.com/99616004/163736850-7b9bf40d-d67d-4aae-99f6-d354004bee15.png">

Step 3: Use the daily return data to create box plots to visualize the volatility of the 4 funds and the S&P 500 

<img width="892" alt="image" src="https://user-images.githubusercontent.com/99616004/163736884-fcff3a73-a69f-4c02-bf83-7c358ceb00f8.png">


Step 4: plot the rolling standard deviation of the 4 portfolios and the S&P 500 (using 21 day rolling window)

<img width="874" alt="image" src="https://user-images.githubusercontent.com/99616004/163736919-c05a0a3c-16f2-4039-b6a4-5b4289686021.png">

Step 5: calculate and Visualize the Sharpe ratios as a bar chart

<img width="875" alt="image" src="https://user-images.githubusercontent.com/99616004/163736961-e4cdcb42-002d-4f56-bba9-61c9d56c5819.png">

Step 5: calculate and  Plot the rolling beta 

<img width="876" alt="image" src="https://user-images.githubusercontent.com/99616004/163737022-e1e88de3-7310-4d73-bd91-70870181940b.png">



Conclution:  

After calculating and visulize return, STD, sharp ratio, beta etc, it was concluded that:
Based on the annualized standard deviation, no portfolio pose more risk than the S&P 500
Based on the rolling standard deviations of only the four fund portfolios, Berkshore Hathaway poses most risk ovearll, except in 2019, Paulson seems to be in par with Berkshore. 
based on sharp ratio, Berkshire Hathaway offsers the best risk-return profile and Paulson offsers the worst
BERKSHIRE HATHAWAY seems more sensitive to move of SP500 than Tiger Global
Finally, we recommend to incude BERKSHIRE HATHAWAY in the firm's suite of fund offserings



## Contributors

Brought to you by TaoNYC.
connorchen7@gmail.com

---

## License

Columbia Fintech Coding Bootcamp
