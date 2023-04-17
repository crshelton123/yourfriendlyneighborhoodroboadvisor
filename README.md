# "Your friendly Neighborhood Robo Advisor!"
## Project: Robo Advisor Market Research
## Code Name: Help Mom Retire!
--- 
### Project Summary
* Problem: We have noticed that while many more self investing options are available to consumers now than ever before, many users still do not enter the investment arena due to lack of knowledge, confidence or thinking they need large funds to get started. 

* Mission: Our goal was to identify the populations with the most need for getting into robo advisors, and which options are the best for them.

* Our Essential Questions
    * Which robo advisors are the best options to get into?

    * Where are the biggest concentrations of population to focus on?

    * Which demographics of the population are the best to market to?
---
### Project Details
* We got the Census.gov API working and used it to pull population data and plot the states with the most population. 
    ![Population](plots/Top_10_states.png)
* We found other data on the Census website and downloaded csvs. 
    * We found the income range by age in the United States and plotted it. This data shows that people in the age range of 45-59 are making the most in their lifetime, and it will likely drop after that. 
         ![Income_by_Age](plots/income_by_age_plot.png)
    * We found data on roboadvisor users that shows only 32% of current users are female, which combined with our age range, makes the target new investors women ages 45-59, hence our project code name! 
    * We also found educational attainment information by gender and filtered it for only women with at least a 7th grade education and above. We plotted the data as well. 
         ![Ed_Females](plots/ed_females_45_59_plot.png)