# Dota 2 Competitive Scene Data Analysis

## Project Overview
This project is a comprehensive data analysis of the Dota 2 competitive scene. The analysis focuses on games played since 2019 and includes a total of 69 plots for visual representation of the data.

## Data Source
The dataset used in this project was obtained from a public repository on GitHub provided by https://github.com/Itzal98. The original dataset can be found at https://github.com/Itzal98/Dota-2-international-tournaments-analysis-2019-2022-/tree/main/Data.

## Data Collection

The data for this project was collected from four different datasets, each providing unique insights into the Dota 2 competitive scene. Prior to the analysis, the data underwent a preprocessing stage where it was cleaned and formatted for further use. This ensured the accuracy and reliability of the results obtained from the analysis.


1. **Match Details Dataset**: This dataset provides detailed information about each match, including the match ID, map, tournament, team, side (radiant/dire), score, result (win/lose), duration, and the heroes picked by each team.

2. **Tournament Prizes Dataset**: This dataset provides information about the prizes won by teams in different tournaments. It includes the tournament name, the place secured by the team, the team name, and the prize amount.

3. **Match Summary Dataset**: This dataset provides a summary of each match, including the match ID, tournament, map, team, side (radiant/dire), score, win (1 for win, 0 for lose), and duration.

4. **Hero Picks Dataset**: This dataset provides information about the heroes picked by each side in each match. It includes the match ID, side (radiant/dire), pick (the order in which the hero was picked), the hero, and win (1 for win, 0 for lose).

These datasets were combined to perform a comprehensive analysis of the Dota 2 competitive scene.

## Analysis
The analysis focuses on visualizations to provide insights into the Dota 2 competitive scene. The visualizations cover various aspects such as:

1. **Teams that played the most**

2. **Teams that won the most**

3. **Heroes that got picked the most**:

4. **Top tournaments by prize money**:

5. **Top teams by prize money**:
   
6. **Percentages of prize money won by teams in each tournament** (for example, OG):
   
7. **Heroes with the highest winning percentage**:
   

And many more...

## Visualizations
The project includes 69 plots that represent various aspects of the data. These plots provide a visual understanding of the trends and patterns in the Dota 2 competitive scene.

## Tools Used

This project was implemented using Python and Jupyter Notebook. The following Python libraries were used:

- **Pandas**: Used for data manipulation and analysis. It provides data structures and functions needed to manipulate structured data.

- **Matplotlib**: A plotting library for Python and NumPy that provides a flexible way to create interactive plots.

- **Seaborn**: A Python data visualization library based on Matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.

- **NumPy**: A Python library used for working with arrays. It also has functions for working in the domain of linear algebra, Fourier transform, and matrices.

These tools and libraries were integral in performing the data analysis and creating the visualizations for this project.


## How to Use

This project is implemented in a Jupyter notebook and the code is well-commented and easy to follow. To use this project:

1. Clone the repository to your local machine.
2. Ensure that you have the necessary Python libraries installed (Pandas, Matplotlib, Seaborn, NumPy).
3. Open the Jupyter notebook and run the cells sequentially.

The datasets used in this project are stored in a specific folder. Please ensure the datasets are in the correct location before running the code.


## Future Work

This project has laid the groundwork for a comprehensive analysis of the Dota 2 competitive scene. However, there are several avenues for future exploration and expansion:

1. **Enhanced Visualizations**: While the current project already includes a robust set of visualizations, there is always room for more. Future work could include the development of additional visualizations to provide deeper insights into the data. This would require the collection and integration of more detailed data, such as information about Dota 2 patches and their impact on gameplay.

2. **Player Analysis**: Another interesting aspect to explore could be the impact of player exchanges within teams. Understanding the dynamics of team composition and how it affects performance could provide valuable insights.

3. **Predictive Modeling**: In the long term, the goal is to build a predictive model that can forecast match outcomes based on historical data. This would involve a more in-depth analysis to understand the correlations and causal relationships within the data. 

These enhancements will not only improve the depth and breadth of the analysis but also increase its utility for the Dota 2 community.



## Contact Information
For any additional questions or comments, please contact me at nika446@outlook.com .
