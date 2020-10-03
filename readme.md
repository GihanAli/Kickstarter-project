# Kickstarter Projects Exploration
## by Gihan Mohamed Ahmed Ali


## Dataset

> The current dataset is collected from Kickstarter websites and contains characeristics of 378,661 kickstarter project. This dataset is available at https://www.kaggle.com/kemical/kickstarter-projects

## Preliminary Wrangling
> dropping columns that won't be analyzed
> removing outliers
> convert 'launched' and 'deadline' features into date types and extracting year to new column
> filtering out observations with launch date before 2009
> filtering out the project states that we are not concerned in predicting, namely; undefined, live, suspended
> integrating canceled with failed state


## Summary of Findings & Key Insights for Presentation

> The visuals have shown that the majority of projects have failed or canceled (around 60%, and 10% repectively) while only 30% have succeeded. This result will be included in the presentation.
> The success of the project is positively correlated with the number of backers and the amount of pledge, however, it is negatively associated with the goal amount and the duration from the launch date to deadline. This result will be included in the presentation.
> The project success is more likely in the music and film & video categories.
> The kickstarters are too optimisitic when determining the goal amount which is relatively in a higher range than the actual pledged amount. This result will be included in the presentation.
> The top fundraising projects falls mainly in the Music and Dance categories. This result will be included in the presentation. 
> Successful projects tend to take shorter fundraising duration while Failed projects tend to take longer duration. This result will be included in the presentation.
> The number of backers is consistently higher in the successful projects compared to failed projects.
