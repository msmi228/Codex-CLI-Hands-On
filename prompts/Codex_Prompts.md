# AmesHousing Codex Prompts

## Prompt 1 — Data Preparation

I am working on a data science assignment using the AmesHousing.csv dataset.

My analytical question is: "How does remodeling status relate to home sale prices, and does this relationship differ depending on the age of the home when controlling for square footage and overall quality?"

First, please create a Jupyter Notebook and use Python with pandas to:

1. Load the AmesHousing.csv dataset.
2. Display the first five rows.
3. Show the dataset dimensions and column names.
4. Check for missing values and duplicate records.
5. Identify the variables needed for my analytical question.
6. Clean only the variables necessary for the analysis.

Keep the Python code simple and easy to understand. Use common libraries and avoid unnecessary functions or advanced techniques.

Explain what cleaning was necessary, and do not proceed with the analysis yet.

## Prompt 2 — Variable Creation

Using the cleaned AmesHousing dataset, prepare the variables needed to answer my analytical question.

1. Create a variable called Remodeled using Year Remod/Add and Year Built. Classify homes as remodeled if Year Remod/Add is greater than Year Built.
2. Create a variable called HomeAge by subtracting Year Built from Yr Sold.
3. Create reasonable home age categories for comparing newer and older homes.
4. Check for invalid values, such as negative home ages.
5. Display a summary table showing the number of remodeled and non-remodeled homes and their average sale prices.

Please explain the new variables briefly and keep the code straightforward. Do not move on to regression yet.

## Prompt 3 — Exploratory Analysis

Now perform exploratory data analysis to investigate how remodeling status relates to home sale prices:

1. Create a summary table comparing remodeled and non-remodeled homes, including the number of homes, average sale price, and median sale price.
2. Create a boxplot comparing sale prices between remodeled and non-remodeled homes.
3. Create a second visualization showing average sale price by home age category and remodeling status.
4. Calculate descriptive statistics for SalePrice, Gr Liv Area, and Overall Qual.
5. Briefly explain any patterns observed.

Use pandas, matplotlib, and seaborn where appropriate. Make the charts clearly labeled and easy to interpret.

Keep the analysis focused on my analytical question and do not make claims about causation.

## Prompt 4 — Regression Analysis

Next, perform a multiple linear regression analysis to determine whether remodeling status is associated with sale price after controlling for other housing characteristics.

Use SalePrice as the dependent variable.

Include these independent variables:

- Remodeled
- HomeAge
- Gr Liv Area
- Overall Qual
- An interaction between Remodeled and HomeAge

Use statsmodels for the regression:

1. Display the regression results.
2. Explain the remodeling coefficient and the remodeling-by-age interaction in plain language.
3. Identify whether the remodeling relationship appears to differ based on home age.
4. Report the R-squared value and relevant p-values.
5. Explain whether remodeling status remains associated with sale price after controlling for square footage and quality.

Do not interpret an association as proof that remodeling causes higher sale prices.

## Prompt 5 — Final Summary

Now that the analysis is complete, write a brief findings section at the bottom of the Notebook and answer my original analytical question:

"How does remodeling status relate to home sale prices, and does this relationship differ depending on the age of the home when controlling for square footage and overall quality?"

Include:

1. What the summary statistics revealed.
2. What the visualizations showed.
3. What the regression results suggest about remodeling status and home age.
4. Whether the findings support an association between remodeling and higher sale prices.
5. One limitation of the analysis.

Use the actual results from the notebook. Do not invent statistics or findings.

Write in a natural, straightforward tone that a graduate student could use to explain the findings to someone without a statistics background.

## Prompt 6 — Final Verification

Please review my entire Jupyter Notebook to verify that it meets the assignment requirements.

Check that:

1. The AmesHousing dataset was successfully loaded and cleaned.
2. The analysis answers my original analytical question.
3. There is at least one summary table.
4. There is at least one visualization.
5. The regression uses the correct variables.
6. The written findings accurately reflect the results.
7. All notebook cells run successfully from beginning to end without errors.

Please identify any mistakes, unsupported conclusions, or unnecessary code.

Keep the notebook organized, simple, and focused. Do not add extra analyses that are not needed for the assignment.
