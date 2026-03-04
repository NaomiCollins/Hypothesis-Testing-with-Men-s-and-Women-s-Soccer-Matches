Hypothesis Testing with Men's and Women's Soccer Matches ⚽📊

I explored an intriguing question in international soccer: are more goals scored in women's matches than in men's? Using historical FIFA World Cup match data, I applied statistical hypothesis testing in R to find an evidence-based answer.

📝 Project Overview

I worked with a major online sports media company dataset, specializing in soccer analysis and reporting. Having followed both men's and women's international soccer matches for several years, my intuition suggested that women's matches see more goals. To confirm this, I applied a valid statistical hypothesis test.
To ensure consistency, I limited the analysis to official FIFA World Cup matches (excluding qualifiers) after 2002-01-01, acknowledging that performances vary across tournaments and the sport has evolved over time.

📊 Data

I created two datasets containing results from every official men's and women's international football match since the 19th century, scraped from a reliable online source:
women_results.csv – Women's FIFA World Cup matches
men_results.csv – Men's FIFA World Cup matches

❓ Research Question

Are more goals scored in women's international soccer matches than in men's?

⚖️ Hypotheses

I assumed a 10% significance level and formulated the following hypotheses:
H0: The mean number of goals scored in women's international soccer matches is the same as men's.
HA: The mean number of goals scored in women's international soccer matches is greater than men's.

💻 Approach

I conducted the analysis in R, performing an appropriate hypothesis test to calculate the p-value. The results were stored in a data frame called result_df with the following columns:
p_val – the p-value of the test
result – "reject" or "fail to reject" the null hypothesis based on the significance level
This approach allowed me to rigorously determine whether there is statistical evidence that more goals are scored in women's matches.

🔍 Key Skills

Statistical hypothesis testing / 
Data analysis and cleaning in R / 
Sports analytics & data storytelling / 
Working with historical sports datasets
