# League of Legends Ranked Game Analysis

**League of Legends Ranked Game Analysis** is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists.

## Dataset Content

* The Dataset I have chosen was sourced from kaggle, and initially created through utilisation of League of Legends API. It provides information pertaining to high level ranked matches played thoughout Season 9 of the game. The primary insights it provides are elements such as the character/champion chosen by each of the 10 players, which team won the match, which team completed side objectives first, and how many they completed.

## Business Requirements

* By focusing on information that would be available before a match has begun, it is possible to make a sort of oracle tool, which provides insights on which team is more likely to win, highlighting metrics such as individual character/champion win rate, overall team synergy, etc.

## Hypothesis and how to validate?

### Hypothesis 1: Using Levene’s Test for Equality of Variances
* Alternative Hypothesis: Champion win rates exhibit a significant negative correlation with their pick rates, where lower popularity scores are associated with higher win rate variance.

* Null Hypothesis: There is no relationship between a champion's pick rate and win rate variance.

### Hypothesis 2: Using Chi-Square Test
* Alternative Hypothesis: Individual champion win rates significantly deviate from a balanced 50% baseline distribution, indicating systemic character imbalance in the current meta.

* Null Hypothesis: Every champion possesses an identical, perfectly balanced win rate of exactly 50%.

### Hypothesis 3: Using Two-Sample Independent T-Test
* Alternative Hypothesis: Highly popular champions have a significantly lower mean win rate compared to moderately popular champions

* Null Hypothesis: There is no significant difference in mean win rates across different popularity tiers.

### Hypothesis 4: Using Binomial Test for Proportions
* Alternative Hypothesis: The win rate of matches played on the Blue Team (Team1) significantly deviates from a 50% distribution, proving the existence of an advantage.

* Null Hypothesis: The Teams are perfectly fair; Blue Team and Red Team win exactly 50% of matches each.

## Project Plan

* Setting up a Kanban board on Trello

* Sourcing the Dataset from Kaggle

* Getting a brief overview of the dataset before establishing objectives.

* Completion of EDA

* Completion of ETL

* Application of Statistical Analysis to answer hypotheses

* Use of Tableau for Dashboarding and Visualisation

* Providing a conclusion in the form of a final analysis

* Overall Evaluation of the project

The plan above was completed in the order of mention. Data was maintained through loading and previewing whenever loaded, to ensure no issues occurred.

## The rationale to map the business requirements to the Data Visualisations

* The goal was to analyse the data in such a manner to allow for the creation of an oracle tool, if one wished to do so. The used hypotheses were helpful to reaching this end as they provided evidence  


The tarrget was tomcreate visuals to show the relation between different variables that have effect on the malaria incidence in Nigeria. The trend lines and Regression plots helped to convey this. •The trend line conveyed a fluctuation in the decrease of incidence. •While the regression line was inaccurate giving a forecast due to probably the model unable to capture the dat properly or migh be some underreporting of the cases.
## Analysis techniques used

* List the data analysis methods used and explain limitations or alternative approaches.
* How did you structure the data analysis techniques? Justify your response.
* Did the data limit you, and did you use an alternative approach to meet these challenges?
* How did you use generative AI tools to help with ideation, design thinking and code optimisation?

## Ethical considerations (optional)

* Feel free to delete this section if this is a data visualisation only (unit 1 or 2) project submission.
* Were there any data privacy, bias or fairness issues with the data?
* How did you overcome any legal or societal issues?

## Dashboard Design (optional)

* Feel free to delete this section if this is a data visualisation only (unit 1 or 2) project submission.
* List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
* Later, during project development, you may revisit your dashboard plan to update a feature (for example, at the beginning of the project, you were confident you would use a given plot to display an insight, but later you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences. 

## Unfixed Bugs

* Please list any unfixed bugs and explain why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap

* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 

## Deployment (optional)

* If this is a Unit 3 Streamlit, Power BI or Tableau Public project, then you can include a link here and explain how you hosted the dashboard.

### Heroku (optional)

* This section is necessary only if you are deploying a Streamlit app to Heroku as part of your submission for units 2 and 3. 
* The App live link is: https://YOUR_APP_NAME.herokuapp.com/ 
* Set the `.python-version` Python version to a [Heroku-22](https://devcenter.heroku.com/articles/python-support#supported-runtimes) stack currently supported version.
* The project was deployed to Heroku using the following steps.

1. Log in to Heroku and create an App
2. From the Deploy tab, select GitHub as the deployment method.
3. Select your repository name and click Search. Once it is found, click Connect.
4. Select the branch you want to deploy, then click Deploy Branch.
5. The deployment process should happen smoothly if all deployment files are fully functional. Click the button Open App at the top of the page to access your App.
6. If the slug size is too large, then add large files not required for the app to the `.slugignore` file.

## Main Data Analysis Libraries

* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.

## Credits

* In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials; however, it is important to be very specific about these sources to avoid plagiarism. 
* You can break the credits section into Content and Media, depending on what you include in your project. 

### Content 

- The text for the Home page was taken from the Wikipedia Article A
- Instructions on how to implement form validation were taken from a [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site



## Acknowledgements (optional)

* Thank the people who supported this project.
