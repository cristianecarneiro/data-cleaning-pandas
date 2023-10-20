# Project |  Data Cleaning  -  Cristiane Carneiro 

Cleaning 'Global Shark Attacks' databased available on kaggle. 

## Intro and objectives 

XXX

## Key insights 

XXX

## Data cleaning log and rationale 

### Process one 

XXX

### Process two  

XXX

### Process three

XXX

## Back-up 

### Data base 

- Database source: https://www.kaggle.com/datasets/teajay/global-shark-attacks/data
- Downloaded on Oct 20th 2023
- Full dataset downloaded on 29-09-2016 from original sourceEach row corresponds to a shark attack.

#### Rows 

- Each row corresponds to a shark attack

#### Columns  

- Case Number: shark attack ID 
- Date: date of attack 
- Year: year of attack 
- Type: type of attack 
- Country: country of attack 
- Area: area of attack (e.g., state)
- Location: beach of attack 
- Activity: what the victim was doing when attacked 
- Name: name of victim
- Sex: gender of victim (F/M)
- Age: age of victim on the time of attack 
- Injury: description of injury provoked by the attack 
- Fatal (Y/N): whether the attack caused a fatality (Y/N)
- Time: time of attack 
- Species: species of shark which attacked the victim 
- Investigator or Source: source of attack's value entry 
- pdf: pdf file to individual case 
- href formula: web link to pdf file   
- href: web link to pdf file 
- Case Number: shark attack ID (to be evaluated if consistent with first column) 
- Case Number: (to be evaluated if consistent with first column) 
- original order: order's in which the attacks occured  

### Files Tree 
- clean.ipynb: log of data cleaning techniques used
- analysis.ipynb : data that validates the conclusions based initial hypotesis

### To Do's (to be deleted)
- Explore the data and write down what you have found you can use: df.describe(), df["column"], etc.
- Use at least 5 data cleaning techniques inside a file named clean.ipynb null values, columns drop, duplicated data, string manipulation, apply fn, categorize, regex, etc.
- Show data that validates the conclusions based on your hypoteses in a file named analysis.ipynb 
