# Loan Qualifier App

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

Step 1: run App.py
```python
python app.py
```
Step 2: user is prompted to type in the input file path

<img width="514" alt="image" src="https://user-images.githubusercontent.com/99616004/162578671-70b7a4f2-d368-4519-9b09-138052ca5cb1.png">

Step 3: user is prompted to type in info such as Cretit Score, income, etc

<img width="389" alt="image" src="https://user-images.githubusercontent.com/99616004/162579016-d2a32538-1d70-4b9b-b078-06f4c45fb223.png">

Step 4: 

  a. if no loan is found, system exit

  <img width="309" alt="Screen Shot 2022-04-09 at 10 24 51 AM" src="https://user-images.githubusercontent.com/99616004/162579077-da826a02-7f94-4e11-b2a0-e4bc8f5458d8.png">

  b. if qualifying loans are found, display number of loan found

  <img width="302" alt="image" src="https://user-images.githubusercontent.com/99616004/162579161-3dcca13d-3406-4fcc-a091-3313b6229035.png">

Step 5: user is asked if he/she wants to save the output to csv file

  a. if user choose not to save file, exit with msg below

  <img width="352" alt="image" src="https://user-images.githubusercontent.com/99616004/162579247-441a2c85-4719-4b5c-99a1-f50e150635b3.png">

  a. if user choose to save file, user is promped to input oupput file path

  <img width="524" alt="image" src="https://user-images.githubusercontent.com/99616004/162579300-1e83cfdc-b1c9-4990-a51a-44d51f6dd171.png">



Step 6: finally you should see beow output in the csv file.

  <img width="706" alt="image" src="https://user-images.githubusercontent.com/99616004/161436456-40f31e4a-6427-449f-a9da-e33e925e62bc.png">


## Contributors

Brought to you by TaoNYC.
connorchen7@gmail.com

---

## License

Columbia Fintech Coding Bootcamp
