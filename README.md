![Status](https://img.shields.io/badge/Status-Project%20Complete-brightgreen)
# Analysing airline profitability in FY 2022/23

*Jupyter notebook (online version): [click here](https://nbviewer.org/github/darrendube/airline-profitability-analysis/blob/main/notebook.ipynb)*

The aviation industry was hit severely by COVID-19 in 2020 and 2021, with demand falling to about a third of what it was pre-pandemic. The industry has long since recovered, but this recovery has not been equal - some airlines still struggle to return to pre-pandemic profit levels, while others have bounced back much faster. My goal was to investigate the factors that help explain these differences in recovery rate and to identify what set the airlines that recovered fast apart from those that didn't.

## Data

Due to the limited availability of data of this kind online, I collected the data manually, relying on airlines' annual reports.

Number of observations: **100**  
Number of predictors: **9**

Download the dataset [here](https://github.com/darrendube/airline-profitability-analysis/blob/4a95508e6ffcfbdbd58906811ded3b95cf411cfb/airline_data.csv).

## Tools used

- `numpy` - data preprocessing, feature engineering, model building, and diagnostics
- `pandas`, `matplotlib`, `seaborn` - data visualisation, particularly in Exploratory Data Analysis (EDA)

## Main Findings
*(click [here](https://nbviewer.org/github/darrendube/airline-profitability-analysis/blob/main/notebook.ipynb#Results) for a more comprehensive discussion on these findings)*

1. Airlines that flew fuller planes were more profitable - an extra seat filled per 100 seats resulted in a \$43.2 million increase in profit
2. An airlines number of routes was found **not** to be a strong predictor of profit
3. Low-cost carriers were less profitable coming out of the pandemic than full-service carriers
4. Legacy airlines earned higher profit coming out of COVID
5. Airlines that were able to get an additional flight hour out of each aircraft per day could increase profit by about \$160 million

## How to Run

1. Clone this repository: `git clone git@github.com:darrendube/airline-profitability-analysis.git`
2. Set up a Python environment
3. Install `numpy`, `pandas`, `matplotlib`, `seaborn`
4. Start up Jupyter and run the notebook

## Author
Created by Darren Dube  
🔗 [LinkedIn](https://linkedin.com/in/darrendube)  
🌐 [darrendube.github.io](https://darrendube.github.io/)  
