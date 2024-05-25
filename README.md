# The World Happiness Analysis:

# Introduction:

The goal of this project is to perform an in-depth analysis of the World Happiness Report dataset to uncover meaningful insights about global happiness trends. This analysis aims to help understand the factors influencing happiness across different countries and regions, and how these factors have evolved over time. By leveraging SQL queries and visualizations, I have tried to extract valuable information that can inform policy-making decisions and improve overall well-being.

# Dataset: 

The World Happiness Report is a landmark survey of the state of global happiness . The report continues to gain global recognition as governments, organizations and civil society increasingly use happiness indicators to inform their policy-making decisions. Leading experts across fields – economics, psychology, survey analysis, national statistics, health, public policy and more – describe how measurements of well-being can be used effectively to assess the progress of nations. The reports review the state of happiness in the world today and show how the new science of happiness explains personal and national variations in happiness.


Here's a brief explanation of each column in the dataset:

**Country name:** Name of the country.

**Year:** Year column represents the specific year for which the happiness data and related metrics were recorded. 

**Life Ladder:** The happiness score for each country, based on responses to the Cantril Ladder question that asks respondents to think of a ladder, with the best possible life for them being a 10, and the worst possible life being a 0.

**Log GDP per capita:** The natural logarithm of the country's GDP per capita, adjusted for purchasing power parity (PPP) to account for differences in the cost of living between countries.

**Social support:** The national average of binary responses(either 0 or 1 representing No/Yes) to the question about having relatives or friends to count on in times of trouble.

**Healthy life expectancy:** The average number of years a newborn infant would live in good health, based on mortality rates and life expectancy at different ages.

**Freedom to make life choices:** The national average of responses to the question about satisfaction with freedom to choose what to do with one's life.

**Generosity:** The residual of regressing the national average of responses to the question about donating money to charity on GDP per capita.

**Perceptions of corruption:** The national average of survey responses to questions about the perceived extent of corruption in the government and businesses.

**Positive affect:** The national average of responses to questions about positive emotions experienced yesterday.

**Negative affect:** The national average of responses to questions about negative emotions experienced yesterday.


# Analysis & Insights:

🔍Detailed Analysis and SQL queries? Check them out here: [World Happiness Analysis](/World%20Happiness%20Analysis.ipynb/)

- Happiness scores have fluctuated over the years, reflecting global and regional events. The overall trend shows minor fluctuations around an average score of approximately 5.

- Countries like Finland, Iceland, and Denmark consistently rank among the happiest, indicating robust social support, high freedom, and low corruption perceptions.

- Afghanistan, Malawi, and Botswana rank among the least happy, often due to poor economic conditions, low social support, and high corruption perceptions.

- Strong positive correlations are observed between happiness and social support, healthy life expectancy, and freedom to make life choices.

- Negative correlations are observed with perceptions of corruption and negative affect.

# Conclusion: 

- This analysis highlights the complex interplay of social, economic, and emotional factors that contribute to national happiness. 

- Key factors such as social support, healthy life expectancy, freedom to make life choices, and low perceptions of corruption are crucial for enhancing happiness. 

- These insights provide valuable guidance for policymakers and researchers aiming to improve well-being and overall happiness at both personal and national levels.