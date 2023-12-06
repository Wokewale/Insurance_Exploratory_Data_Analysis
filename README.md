# Insurance_Exploratory_Data_Analysis
# Background
In 2022, concern was raised over the rapid increase in insurance premiums, an integral component of US healthcare insurance. For many years, several polls has found that the high cost of health care is a burden on U.S. families, and that health care costs factor into decisions about insurance coverage and care seeking. These costs also rank as a top financial worry. This data note summarizes recent polls on the public’s experiences with health care costs. Main takeaways include:

About half of U.S. adults say they have difficulty affording health care costs. About four in ten U.S. adults say they have delayed or gone without medical care in the last year due to cost, with dental services being the most common type of care adults report putting off due to cost.

Substantial shares of adults 65 or older report difficulty paying for various aspects of health care, especially services not generally covered by Medicare, such as hearing services, dental and prescription drug costs.

The cost of health care often prevents people from getting needed care or filling prescriptions. About a quarter of adults say they or family member in their household have not filled a prescription, cut pills in half, or skipped doses of medicine in the last year because of the cost, with larger shares of those in households with lower incomes, Black and Hispanic adults, and women reporting this.

High health care costs disproportionately affect uninsured adults, Black and Hispanic adults, and those with lower incomes.

Larger shares of U.S. adults in each of these groups report difficulty affording various types of care and delaying or forgoing medical care due to the cost.

Those who are covered by health insurance are not immune to the burden of health care costs.

About one-third of insured adults worry about affording their monthly health insurance premium, and 44% worry about affording their deductible before health insurance kicks in.

Health care debt is a burden for a large share of Americans. About four in ten adults (41%) report having debt due to medical or dental bills including debts owed to credit cards, collections agencies, family and friends, banks, and other lenders to pay for their health care costs, with disproportionate shares of Black and Hispanic adults, women, parents, those with low incomes, and uninsured adults saying they have health care debt.

Affording gasoline and transportation costs is now a top worry for Americans followed by unexpected medical bills. While worry over gasoline and transportation costs has risen markedly since 2020, significant shares of adults still say they are worried about affording medical costs such as unexpected bills, deductibles, and long-term care services for themselves or a family member.

# Objective:
To visualize various variables influencing insurance charges in US.

# Basic Questions:

how do you identify variables that are normally distributed? which one of the variables in insurance dataset is/are normally distributed?
how any females and males are present in this dataset?
What are the mean and median ages of enrollees in this case study?
What is the median number of children in this case study?
is there a difference between bmi mean and median?
Key business questions to be answered and visualized:

Can you identify variables that are highly correlated ?
What region incurred the highest (& least) insurance charges?
Do smokers incur more charges?
is there a statistical difference between average charges incurred by smoker and non-smokers look into shapiro test https://www.statology.org/shapiro-wilk-test-python/, t-test https://www.statology.org/pandas-t-test/ and Mann whitney test https://www.statology.org/mann-whitney-u-test-python/
is there a statistical difference between age of various enrollee insurance plan ? look into : https://www.statology.org/kruskal-wallis-test-python/ & https://www.statology.org/one-way-anova-python/
# Dataset:
enrolleeID: unique identifier of enrollees
age: age of enrollees
gender: gender of enrollee (M or F)
bmi: body mass index of enrollees
children: Number of children by enrollees
smoker: Is the enrollee a smoker (yes or no)
region: geographical location of enrollees
charges: charges in US$ .
plan: insurance plan (bronze, silver, gold, platinum)

# Scripts
project1_insurance_new.ipynb  - Interactive python script

project1_insurance_new.py 
