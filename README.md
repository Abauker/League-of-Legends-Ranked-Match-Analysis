# League of Legends Ranked Match Analysis

**League of Legends Ranked Match Analysis** is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists.

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

* The goal was to analyse the data in such a manner to allow for the creation of an oracle tool, if one wished to do so. The used hypotheses were helpful to reaching this end as they provided evidence of preference towards certain elements, in the form of certain champions performing at a greater level than others.

## Analysis techniques used

The following techniques were used:

### EDA

* A basic Exploratory Data Analysis in order to give myself a brief overview of the data prior to interaction.

### ETL

* An ETL, in which I extracted the data, transformed it to suit my needs, and loaded the now transformed dataset for further use, such as in statistical analysis.

## Dashboard Design

The dashboard was created using Tableau.
First, the cleaned data was loaded onto tableau, and then used to generate a dashboard, by creating visualisations related to each of the 4 hypotheses presented earlier.

## Development Roadmap

* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 

## Main Data Analysis Libraries

The primary python scripts utilised were as follows:

For data handling and manipulation, pandas was used
For Data Visualisation, matplotlib was used
## Credits

* Co-pilot was utilised to aid me in the creation of some areas of code, which was mentioned in those areas.
* The dataset was sourced from Kaggle, and was mentioned previously.

### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site