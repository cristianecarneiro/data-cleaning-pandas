# Project |  Data Cleaning  -  Cristiane Carneiro 

Cleaning 'Global Shark Attacks' databased available on kaggle. 

![skark_picture](https://github.com/cristianecarneiro/data-cleaning-pandas/blob/main/3_img/tubarao-perigoso-debaixo-d-agua.jpg)


## Intro and objectives 

- This is a data cleaning exercise undertaken during IronHack's Data Analytics BootCamp 
- The goal of the exercise was to clean DB 'sharks' guided by an analysis objective (i.e, prioritize variables relevant to the analysis' 
- We were given the following conditions: 1) no columns should be deleted 2) the final databased should have >=2500 rows
- As an analysis objective, I will understand the fatality of shark attacks vs. a set of selected variables 

## Key insights 

- While the analysis itself was a secondary objective in this exercises, we can draw some insights: 
+ Victims in the USA were less like to have fatal accidents 
+ Victims who were surfing where also less likely to have fatal accidents (maybe they continued surfing away, or hit the shark with the board?)
+ Victims who were swimming were more likely to have fatal accidents (hard to swim away at full speed after an attack?)

## Data cleaning log  

- The data cleaning process/techniques can be found in file clean.ipynb

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
- Case Number.1: shark attack ID (to be evaluated if consistent with first column) 
- Case Number.2: (to be evaluated if consistent with first column) 
- original order: order's in which the attacks occured  