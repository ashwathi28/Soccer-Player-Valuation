# Soccer-Player-Valuation-An-Analysis-of-Player-Prices-in-the-Transfer-Market

## Abstract:

  The project "Exploring Soccer Player Valuation: An Analysis of Player Prices in the Transfer Market" analyzes the soccer transfer market and player valuations. The     goal is to explore the factors contributing to player prices and develop insights to help clubs decide about player acquisitions. This is achieved through data         scraping, cleaning, processing, and the use of statistical and machine learning techniques to find relationships between player attributes and value. Moreover,         player values are predicted using other available information via different modeling techniques. Models are compared based on accuracy and the best one is chosen.     Finally, the predicted values are compared with actual values to evaluate how well the model provides a comprehensive analysis of player valuations and contributes     to a better understanding of the transfer market.

## Data:

  The data was collected from the SoFIFA website for the year 2023 and written into a csv file for our analysis. There are 18 features and 4892 observations in the       dataset and the variables are of both object as well as numeric type.
  
  Cleaned the data by removing unnecessary columns, fixing missing or incorrect values, and converting the data types as needed. Dropped the 'Special' and 'Kit Number'   columns, and converted the 'Value', 'Wage', and 'Release Clause' columns to more appropriate units.
  
  Performed Exploratory Data Analysis on the dataset to better understand the relationships between the variables and identify any patterns or trends such as finding     the top 5 players based on their value and overall rating, analyzing the average value by player position, creating visualizations to show the distribution of player   positions and preferred foot, and calculating correlations between variables.

## Methodology:

  Model Building: Building a model involves selecting the right independent variables and splitting the data into training and testing sets in a 3:1 ratio. In order to   determine whether lasso, ridge, or elastic net regression performed best, a cross-validation iterative elastic net regression model was created. The values of         players were also predicted using Random Forest regression.
  
  Model Evaluation: Accuracy metrics Mean Squared Error (MSE) and R-Squared value were used to assess the models’ performance. The final model was assessed using a       density map between projected and actual values.

![image](https://user-images.githubusercontent.com/130589478/235369022-378cb35f-689f-44b2-b821-95fddef06c10.png)

## Conclusion:

  The analysis showed that the value variable is linearly related to the overall rating when the overall rating is greater than 70. The mean value of players based on   position and left, or right-footedness are different. The results also highlighted that the variables which have a high correlation with value are Overall Rating,     Potential Rating, Wage, and Release Clause. It is crucial to select appropriate variables, as independent variables are correlated with each other, and the model can   be overfitted. The Random Forest Regression model was found to be the best-performing model compared to Ridge, Lasso, or ElasticNet Regression, with a lower mean       squared error and a higher r-squared value. The model was also used to compare the predicted and actual values, and the density plot shows that the model can predict   the data effectively. Lastly, the analysis identified the most overvalued and undervalued players according to the model, which can assist soccer teams in             identifying potential bargains or overpriced players when buying or selling players.

  Overall, this project provides valuable insights into the factors that influence the valuation of soccer players and the best techniques to use for predicting player   values. It has practical implications for soccer teams, helping them to make informed decisions in the transfer market.
  
## Contributors:
  Ashwathi Ajayan Nambiar (https://github.com/ashwathi28)
  
  Kshitij Jain (https://github.com/kshitij107)
  
  Mohammed Mafaz Nadherssa (https://github.com/mafazazhaar)
