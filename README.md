# Uber-and-Lyft-Price-Prediction

**Contributors**

Yu-Chin Chen, I-An Chien, Shuo-Ming Kuo, Yi-Cheng Chung

**Background**

As residents living in the Boston area, we benefit from a convenient public transportation system, including commuter rail, subway lines, and bus routes. 
However, despite these options, sometimes schedules or routes may not fit our specific needs, prompting us to rely on services like Uber and Lyft for convenience. 
These ride-sharing apps have become an integral part of transportation in the Boston area, and pricing is an important factor in the decision-making process. 
When considering whether to choose Uber or Lyft, the first thing that comes to mind is price, as people often open both apps to compare and choose the more economical option.

Several factors contribute to price fluctuations on these platforms. For example, demand and supply dynamics play a crucial role, with peak periods or high demand 
causing higher price. In addition, external factors such as weather conditions, traffic or distance can also affect the cost of a ride. The availability of different 
vehicle types and service levels also results in different price points.

**Conclusion**

In conclusion, the XGBoost regression model demonstrated the best performance for predicting both Uber and Lyft prices, with the lowest root mean squared error scores compared to 
other models tested. By conducting supervised machine learning to predict Uber and Lyft surge prices, we learned the importance of finding the most accurate and cost-effective 
machine learning model to solve business problems with limited resources. With time and compute power limitations, we needed to use a select number of hyperparameters to tune our models 
and find the best prediction model for Uber and Lyft separately. Feature importance analysis found that the distance traveled was the most influential factor affecting price predictions 
for both Uber and Lyft. This aligns with intuition as trip distance directly impacts the fare amount. Other top predictors were location attributes like pick-up location, destination, and time period.
Comparisons of actual versus predicted price values showed the XGBoost models were relatively accurate, with most predictions closely aligned or slightly under-estimating the actual fares. 
The predicted prices fell within a $5 difference for a majority of the test cases.

Overall, our analysis and modeling provides an effective framework to predict Uber and Lyft pricing based on a variety of features like trip details, geographic locations, vehicle types 
and external factors like weather. The XGBoost approach outperformed other regression models, demonstrating feasibility to deliver accurate price estimates to riders using historical Uber and Lyft data trends. With some refinement, 
the predictive models show promise to be integrated into passenger travel planning and budgeting use cases going forward.
