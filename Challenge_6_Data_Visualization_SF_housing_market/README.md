# Data Visualization of San Francisco housing market

This is a Python application allowing users to do data visualization on on information about rent, sale price to make a investment decision (for example buy-and-rent) 

 The application works by importing housing data in SF from csv and use groupby function to calculate aggregated data according to year and neighborhood. Then use hvplot to visualize the data trend
 

 
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

Step 1: run san_francisco_housing.ipynb
```python
python san_francisco_housing.ipynb
```
Step 2: Calculate and Plot the Housing Units per Year

<img width="702" alt="image" src="https://user-images.githubusercontent.com/99616004/165968093-33f570ff-301e-43fa-8450-54fad80fd565.png">

Step 3: Calculate and Plot the Average Sale Prices per Square Foot

<img width="877" alt="image" src="https://user-images.githubusercontent.com/99616004/165968198-4e7c246d-73a5-4421-922d-c7953133e7c3.png">



Step 4: Compare the Average Sale Prices by Neighborhood

<img width="877" alt="image" src="https://user-images.githubusercontent.com/99616004/165968651-bb95f339-7cf0-4332-b9f4-7b2583f0e8fb.png">

Step 5: Build an Interactive Neighborhood Map

<img width="869" alt="image" src="https://user-images.githubusercontent.com/99616004/165968920-2505b418-5bdc-4f81-aa8c-9b149b3d669c.png">



Conclution:  

According to historical data, it looks it would be a poetential good strategy for buy and rent because rent income will potentially outgrow sale price. However, be careful on some neighborhood for example: 
Anza Vista where sale price came down, so that it would not be wise to buy because investor might incur asset value shrink over the long run



## Contributors

Brought to you by TaoNYC.
connorchen7@gmail.com

---

## License

Columbia Fintech Coding Bootcamp
