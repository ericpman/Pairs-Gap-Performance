# Pairs-Gap-Performance

## Overview
This program measures the odds and average performance of a selected stock pair from open to close after an overnight gap, offering insights for traders on potential performance based on specific overnight gap percentages.

## Libraries
pandas  
yfinance  

## Usage
The program will prompt the user to enter the following inputs:

1) 
1. **Stock 1**: Enter the first stock symbol for the pair.


![Screenshot 2024-10-31 125718](https://github.com/user-attachments/assets/fc166a16-e7c5-4dbb-b2ec-dc512381ac6a)



2) **Stock 2**: Enter the second stock symbol for the pair.
 
  ![Screenshot 2024-10-31 125205](https://github.com/user-attachments/assets/907a6d63-5303-44cb-82c8-3201d740918b)


3) **Overnight Gap Percentage**: Enter the gap percentage in absolute terms. The program will analyze performance for both positive and negative versions of the gap entered.

 ![Screenshot 2024-10-31 125216](https://github.com/user-attachments/assets/6795d792-a88c-4a83-a36a-c60632cd64c4)


## Output
The program generates the following output:

- **Total Performance**: Combined performance of the pair from open to close based on the specified gap percentage + or - 0.2%.
- **Average Performance**: Average open-to-close performance for gap value + or - 0.2%
- **Odds**: Probability of positive and negative open-to-close performance for the specified gap value + or - 0.2%.


The goal of the program is to give a trader a probability basis for performance of his or her pair on an open to close basis. It uses the degree of an overnight gap to calculate this probabilty and potential performance.

## Customization
Users can adjust the date range to fit their analysis period of choice by specifying preferred start and end dates within the code.


