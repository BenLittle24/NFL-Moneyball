# **NFL Moneyball Data Analysis and Visualization**

## **Overview**
This project explores the application of “Moneyball” principles to NFL analytics, analyzing player performance metrics alongside salary and team success. The goal was to uncover undervalued players, highlight versatile contributors, and provide interactive tools for the users’ decision-making. By leveraging visual storytelling, the project aims to deliver insights for analysts, coaches, and maybe even fantasy football enthusiasts.

## **Motivation**
Inspired by the success of Moneyball in baseball, this project applies similar methodologies to NFL data to assess traditional player valuation approaches. The multidimensional nature of football player contributions makes it an ideal candidate for advanced visualizations and interactive dashboards.

## **Dataset**
- **Source**: Performance metrics were sourced from Pro-Football-Reference, while salary data was gathered from OverTheCap.
- **Key Features**:
  - Categorical: Player Name, Team, Position.
  - Quantitative: Passing Yards, Rushing Yards, Receiving Yards, Total TDs, Salary, Team W-L%.
  - Derived: Salary-to-Team-Success Ratio (STSR), Normalized Yards/TDs/Salary, Player Value Ratios.
- **Data Cleaning and Processing**:
  - Addressed or cleaned missing salary data (~25% of players).
  - Standardized player names for merging datasets.
  - Manually (but reluctantly) aligned team abbreviations to ensure consistency.

For more details, see the [Full Writeup](Presentation%20Writeup.pdf) or the [Video Presentation](https://drive.google.com/file/d/1nB1JWZnG_M88Bu10kq3dJKX13S0jRvkr/view?usp=sharing)!

## **Tools Used**
- **Google Sheets**: Initial data collection, cleaning, and preprocessing.
- **Tableau**: Interactive visualizations and dashboards.

## **Key Visualizations**
1. **Scatter Plot**: Offensive player contributions (passing/rushing/receiving or total yards) vs. team success (W-L%).
2. **Salary-to-Performance Bar Chart**: Highlights undervalued and overpaid players using Salary-to-Team-Success Ratio (STSR).
3. **Offensive Versatility Heatmap**: Visualizes player versatility across passing, rushing, and receiving dimensions.

*ToDo: To interact with these visualizations, explore the Tableau dashboard [here](link_to_public_Tableau)!*

## **Results**
- **Undervalued Players**: Identified high-impact players with low salaries, including:
  - **Quarterbacks**: Brock Purdy, Patrick Mahomes (surprisingly).
  - **Wide Receivers**: Amon-Ra St. Brown, Puka Nacua.
- **Salary Disparities**: Highlighted inefficiencies in spending, such as high salaries with low contributions.
- **Versatility Insights**: While versatility was less prominent than expected, the heatmap revealed both versatile players (Justin Fields, LaMarvelous (MV3?) Jackson) and highly specialized players (Stefon Diggs).
  - **Note**: As mentioned in the video presentation, the Versatility Heatmap produced unexpected results. There is a theoretical discussion about why/how this happened, and if this was a consequence of the analysis or the nature of the NFL. That can be found in the [writeup](Presentation%20Writeup.pdf) if you're interested! 

## **Challenges and Lessons Learned**
- **Data Limitations**: Salary data was incomplete for about 25% of players, impacting some analyses.
- **Normalization Issues**: The heatmap implementation emphasized the rarity of versatility, leading to questions regarding the scaling methods used in the analysis and the level of player specialization in the NFL. 
- **Data Concerns**: Due to ambiguous data sources, there is a potential misalignment between performance data and salary data seasons, introducing uncertainty. 

## **Explore the Project**
- For a demonstration/explanation of the interactive visualizations, check out the [Video Presentation](https://drive.google.com/file/d/1nB1JWZnG_M88Bu10kq3dJKX13S0jRvkr/view?usp=sharing)!
- For more technical detail and discussion, the [Final Writeup](Presentation%20Writeup.pdf) is what you're looking for. 
- If you'd like to do your own analysis, the [Interactive Tableau Dashboard](placeholder) will be available as soon as I figure out how to make it worth your while. At the time of writing, uploading the data and visualizations to a public Tableau server is limiting functionality. 

