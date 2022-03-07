# Project Title

It is a software run to help the user to choose the qualifying loans based on the provided criteria. The qualified loans will be generated in a new sv file.
---

## Technologies

Python with Fire and Questionary are being used.

---

## Installation Guide
- Install Python (Refer python installation guide), Fire and questionary
- checkout git repository (https://github.com/Ahmedfadiya/Module-2-challenge.git)
- navigate to the folder

## Usage


1. Navigate to the current folder in terminal 
2. run Python app.py
3. provide the file path to the rate sheet csv file which contains list of banks, with the min loan requirement data.
4. Input the value 
5. provide file name to a new csv output file.
6. following is the sample command that was run.
---
PS C:\Users\ahmed\desktop\Challenge_Folder\Module 2 challenge\Starter_Code\loan_qualifier_app> python app.py
- Enter a file path to a rate-sheet (.csv): ./data/daily_rate_sheet.csv
- What's your credit score? 750
- What's your current amount of monthly debt? 3000
- What's your total monthly income? 20000
- What's your desired loan amount? 80000
- What's your home value? 350000
The monthly debt to income ratio is 0.15
The loan to value ratio is 0.23.
Found 15 qualifying loans
- Enter output file path ./approved_loan_list.csv
./approved_loan_list.csv

## Contributors

Fadiya Ahmed | ahmedfadiya@hotmail.com
---

## License

GPL License