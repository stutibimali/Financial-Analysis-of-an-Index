# Financial Analysis of S&P 500 Index

This project involves performing a financial analysis of the S&P 500 companies dataset to uncover various insights related to stock performance and company characteristics. The dataset includes details about companies listed in the S&P 500 index, such as stock prices, earnings, market capitalization, and more.

## Project Breakdown

### Task 1: Housekeeping
1. **Load Data into Pandas DataFrame**  
   The dataset is loaded into a Pandas DataFrame for analysis.

2. **Rename Columns to Remove Spaces**  
   Columns are renamed to remove spaces for better accessibility.

3. **Convert Market Cap and EBITDA**  
   - Market Cap is converted into billions.
   - EBITDA is converted into millions for easier interpretation.

### Task 2: Sector-Based Analysis
1. **Average Price/Earnings and Market Cap by Sector**  
   - Compute average Price/Earnings and Market Cap for each sector.
   - Display the top and bottom 5 sectors by highest and lowest average Price/Earnings.
   - Display the top and bottom 5 sectors by highest and lowest average Market Cap.

### Task 3: Companies with Losses
1. **Identify Non-Profitable Companies**  
   Find companies that are not making any profits based on EBITDA and display the 5 largest non-profitable companies.

### Task 4: Top 3 Sectors in S&P
1. **Sector Count**  
   Compute the number of companies in each sector and display the top 3 sectors with the maximum number of companies.
   - Display the bottom 3 sectors with the least number of companies.

### Task 5: Largest and Smallest Companies by Market Cap
1. **Identify Largest and Smallest Companies**  
   Find the 3 largest and smallest companies by Market Cap.

## Technologies Used

- Python
- Pandas
- Jupyter Notebooks (for analysis)

## Dataset

The dataset used in this project includes financial data for all S&P 500 companies and can be accessed via the following link:

[Link to Dataset](https://raw.githubusercontent.com/datasets/s-and-p-500-companies-financials/refs/heads/main/data/constituents-financials.csv)

## Installation

To run this project, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/your-username/sp500-financial-analysis.git
cd sp500-financial-analysis
pip install -r requirements.txt
```
License
This project is licensed under the MIT License.
