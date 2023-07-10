# Euro Cup Soccer Challenge

This repository contains a dataset related to the Euro Cup Soccer Challenge. The dataset comprises match-related information for the tournament, including details on participating teams, goals scored, shooting accuracy, total shots, disciplinary actions (Yellow Cards and Red Cards), and more. The dataset offers valuable insights into team performance, discipline, and statistical metrics for analysis. The repository provides resources such as code, scripts, and notebooks to explore and analyze the dataset, allowing users to gain a deeper understanding of the Euro Cup Soccer Challenge.

![Image Alt Text](https://wallpapercave.com/dwp1x/wp6960696.jpg)




## Scenario
You are a sports data analyst and you have been tasked with summarizing data from the matches from a previous EuroCup. Your manager would like the following questions answered.
## Get the Data
data = pd.read_csv('https://raw.githubusercontent.com/guipsamora/pandas_exercises/master/02_Filtering_%26_Sorting/Euro12/Euro_2012_stats_TEAM.csv', sep=',')
## Link to the Dataset
https://raw.githubusercontent.com/guipsamora/pandas_exercises/master/02_Filtering_%26_Sorting/Euro12/Euro_2012_stats_TEAM.csv
## Questions
- How many teams participated in the Euro2012?
- What is the number of columns in the dataset?
- View only the columns Team, Yellow Cards and Red Cards and assign them to a dataframe called discipline.
- Sort the teams by Red Cards, then to Yellow Cards.
- Calculate the mean Yellow Cards given per Team.
- Filter teams that scored more than 6 goals.
- Select the teams that start with the letter G.
- Select the first 7 columns.
- Select all columns except the last 3.
- Present only the Shooting Accuracy from England, Italy and Russia.
## Data Analysis Workflow
- **Data Extraction:** Code snippets for extracting sales data from Euro Cup Soccer databases or other relevant sources, specifically focused on data extraction related to match statistics, player performance, or team standings.

- **Data Cleaning and Preprocessing:** Scripts and notebooks designed for cleaning and preprocessing raw Euro Cup Soccer data, ensuring it is ready for analysis.

- **Exploratory Data Analysis:** Jupyter notebooks dedicated to conducting exploratory data analysis on the Euro Cup Soccer data, aiming to identify patterns, trends, and correlations in match outcomes, player statistics, or team performance.
## Tools Used For Analysis
- Jupyter Notebook
- Pyhton
- Libraries : Pandas, Numpy
## Key takeaways
- The EuroCup tournament featured 16 participating teams.
- The dataset consisted of 35 columns containing match-related information.
- A new dataframe named "discipline" was created, specifically including the columns for Team, Yellow Cards, and Red Cards.
- Teams like Denmark, Germany, England, Netherlands, and Ukraine demonstrated good discipline by not receiving any red cards.
- The mean number of yellow cards per team was calculated to be 7.4375, providing an average measure of aggression or fouls committed.
- Germany and Spain were identified as high-scoring teams, scoring more than 6 goals in the tournament.
- Germany and Greece were the teams whose names started with the letter "G."
- The first 7 columns of the dataset provided insights into team names, goals scored, shooting accuracy, and total shots.
- All columns, except the last 3, offered a comprehensive set of attributes for further analysis of team performance.
- England had the highest shooting accuracy at 50.0%, followed by Italy at 43.0%, and Russia at 22.5%
## Acknowledgements

 - This project was undertaken as a challenge presented by Data in Motion (https://d-i-motion.com/) 
- I would like to express my gratitude to Data in Motion for providing the opportunity to work on this project and gain valuable insights into the analysis of sales data in the food industry.


## Support
👨‍🚀 Show your support
Give a ⭐️ if this project helped you!
## Feedback
- If you have any feedback, please reach out to me 😃(https://www.linkedin.com/in/sanjay-divate/)
- Your feedback is incredibly valuable to me, and I genuinely appreciate your time and support in helping me make this project better.
