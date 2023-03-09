# GroupProject_StockPriceAnalysisAndVisualization
Using Jupyter, pandas, NumPy, Matplotlib, and scikit-learn to perform data exploration, cleaning, visualization, and analysis/interpretation that ultimately inform equity investment recommendation to hypothetical client.

## Background
The files contained in this repository (with the exception of "README.md") constitute my group's submission for the group project carried out at the conclusion of [Python for Data Analysis](https://cpe.ucdavis.edu/section/python-data-analysis), the fourth out of five courses required for completion of the [Python for Data Science, Web and Core Programming Professional Concentration](https://cpe.ucdavis.edu/certificate-program/python-data-science-web-and-core-programming-professional-concentration) offered by the Continuing and Professional Education division of the University of California, Davis. 

Our group received a perfect score on this assignment for our collaborative efforts in generating the contents of "StockPriceAnalysisAndVisualization_Final.ipynb".

## Project Instructions (For Context; Abbreviated)
> As part of this course students will work in groups of 2-3 (groups will be assigned by the instructor) to complete a data analysis project.
> ### Objective
> The objective of this project is for students to get hands-on experience working on robust group data analysis projects with the goal of recommending actionable insights using data from a domain they are interested in. These projects are also meant to serve as a peer-reviewed addition to students' coding portfolios.
> ### Grading Rubric
> The group project is worth 100 points (compared to a weekly assignment, which is worth 20).
> | Item | Expectation | Percentage [of Project Grade] |
> | ----------- | ----------- | ----------- |
> | Introduction | Full points awarded for straightforward introduction including the objective of the report/script and any domain-specific hypotheses your team has going into the analysis. | 10% |
> | Data Exploration | Full points for robust exploration of the data used to explore any nuances or limitations within the data source. | 15% |
> | Data Analysis | Full points for an appropriately executed regression with the interpretation of the output in the context of the objective. This step should also include any needed data cleaning. | 20% |
> | Data Visualization | Full points for at least two appropriate visualizations of your group's data. Visualizations must provide some value to the analysis and be well labeled. | 15% |
> | Recommendation | Full points for clear and actionable takeaway from the analysis. Data analysis is as much about how to code as it is how to use code as a tool to extract insights. | 20% |
> | Readability/Story Telling | Full points for appropriate documentation throughout the report that speaks to the intended logic behind the code. In addition, the notebook must make it clear where each section begins and how each section ties into the objective and final recommendations. | 20% |

## System Requirements and Recommendations
Download and set-up of the (free) [Anaconda Distribution](https://www.anaconda.com/products/distribution), which should contain the latest versions of pandas, NumPy, Jupyter, etc., is recommended prior to accessing "StockPriceAnalysisAndVisualization_Final.ipynb". Once download and set-up are complete, simply open Anaconda Navigator and click "Launch" within the dashboard tile containing the "Jupyter" logo. Upon clicking "Launch" a new tab should open in your browser window. It is within this tab that you should navigate to "StockPriceAnalysisAndVisualization_Final.ipynb".

Once this repository is downloaded to one's personal machine, it is recommended that both "StockPriceAnalysisAndVisualization_Final.ipynb" and "social media stocks 2012-2022.csv" - the input dataset for "StockPriceAnalysisAndVisualization_Final.ipynb" - be kept in-repository so that users need not concern themselves with manually re-declaring the filepath to "social media stocks 2012-2022.csv" within "StockPriceAnalysisAndVisualization_Final.ipynb".

## Dataset Schema
The following dataset - "social media stocks 2012-2022.csv" - was obtained from [Kaggle](https://www.kaggle.com/datasets/prasertk/social-media-stock-prices):

### "social media stocks 2012-2022.csv" Dataset
| Field | Count of Non-Null Values | Data Type | Description |
| ----------- | ----------- | ----------- | ----------- |
| `Date` | 8193 | Object/String | Date for which the floating-point-/decimal-structured data in a given record apply |
| `Symbol` | 8193 | Object/String| Ticker symbol for the company whose stock is described in a given record |
| `Adj Close` | 8193 | Floating-Point/Decimal | Stock's price after adjustments for any relevant splits and dividend distributions |
| `Close` | 8193 | Floating-Point/Decimal | Stock's last trading price during a regular trading session |
| `High` | 8193 | Floating-Point/Decimal | Stock's highest price for the trading session |
| `Low` | 8193 | Floating-Point/Decimal | Stock's lowest price for the trading session |
| `Open` | 8193 | Floating-Point/Decimal | Stock's first trading price during a regular trading session |
| `Volume` | 8193 | Floating-Point/Decimal | Number of shares of that stock traded in that regular trading session |
