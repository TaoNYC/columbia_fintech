# Project Title

This is a Python application allowing users to check what kind of loans they qualify for (if any) from the bank loan list and also be able to save the results in a csv file for future use (if user chooses to). The application works by asking user to input their personal info (credit score, debt, income, etc...) which is used to filter through the bank data loaded from `daily_rate_sheet.csv`, the result of qulaified loans (if any found) will be saved (if user choose to) in the output csv file (to be specified by user)

---

## Technologies

This project leverages python 3.7 +, fire, questionary, pathlib


---

## Installation Guide

Before running the application, first make sure below libaries are installed

```python
  pip install fire
  pip install questionary

```
Alerternatively you can simply just install requirement file included in this folder
```python
  pip install -r requirement.txt

```

---

## Usage

```python
python app.py
```
By finishing launching the app application you should see beow output in the csv file.

<img width="706" alt="image" src="https://user-images.githubusercontent.com/99616004/161436456-40f31e4a-6427-449f-a9da-e33e925e62bc.png">


## Contributors

Brought to you by TaoNYC.
connorchen7@gmail.com

---

## License

Columbia Fintech Coding Bootcamp
