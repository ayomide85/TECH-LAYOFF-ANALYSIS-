# TECH LAYOFF ANALYSIS (2020–2022)
## INTRODUCTION
Across the globe, its estimated in 2022 alone, over 120,000 employees have been laid off by big tech companies such as Meta, Amazon, Netflix and smaller firms and startup as well, which made me curious to analyze the layoff
## ABOUT THE DATASET

The dataset was obtained from Kaggle.com 

https://www.kaggle.com/datasets/swaptr/layoffs-2022.

The dataset is a CSV file with 9 columns.

. Company (Name of the company)

. Location (Location of company headquarters)

. Industry (Industry of the company)

. total_laid_off (Number of employees laid off)

. percentage_laid_off (Percentage of employees laid off)

. date (Date of laid off)

. stage (Stage of funding)

. country (Country)

. Funds_raised (Funds raised by the company (in Millions $)

![l1](https://user-images.githubusercontent.com/78751113/224112263-2739951e-50ae-4ff1-b6e6-da7944d71622.png)

## DATA CLEANING

it's important to detect inaccurate, duplicate, or incomplete data within a dataset to help quality data decision-making.

I cleaned the data with the steps below.

· Blank rows: Null.

· Remove duplicate: one Duplicate found and removed; 1664 unique values remain.

· Missing Values: some missing value was dropped

· Data Type: The data types were checked and corrected

a Number formats: percentage laid off value was formatted to percentage.

b Date value was formatted to short date

c Fund raised was formatted to currency and dollar

· Added columns: some columns were added to gain more insights

a Day column was added from the date column

b Month column was added from the date column

c year column was added from the date column

· Converted the data format into a table format using CTRL+T.


![L2](https://user-images.githubusercontent.com/78751113/224112848-8aca1855-37a1-4ecb-b5a8-053297fcc801.png)

summarized into a Pivot table.

![l7](https://user-images.githubusercontent.com/78751113/224113027-543c82cd-ee03-4a5b-8275-a234da0c407f.png)

## DATA ANALYSIS AND INSIGHT


![layoff analysis 4](https://user-images.githubusercontent.com/78751113/224113183-a45223cd-c96e-4f95-bac2-a34cd02d08ea.png)

Here, we could discover the following insights:

1. The top 3 companies with the most layoffs between 2020 and 2022 were Meta, Amazon, and Uber. Meta had 11,000 layoffs, or about 4.5% of all layoffs, while Amazon and Uber laid off 10,000, and 7,585 staffs respectively.
2. United States layoff approximately 66% of the total layoff, 5 times more than the second country, India.
3. The highest layoff occurred in 2022 despite having the highest number of fundraised.
4. In November 2022, there was a massive layoff than any other months due to the slowing growth and a fear of a possible recession the following year.
5. Approximately 53% of the funds raised were raised by Media and Transportation respectively, that's about more than half of the funds raised.

## Recommendation

Future occurrences of layoff should be prevented through having the appropriate number of staff needed for an organization, cutting of staff benefit instead of lay off, encouraging early retirement, avoid outsourcing, avoid overtime, renegotiating of salary.









