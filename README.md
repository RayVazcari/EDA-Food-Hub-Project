<h1><center><font size=10>Data Science and Business Analytics</center></font></center></h1>
<center>Project 1 - Python Foundations: FoodHub</center></h1><p
<center>Jorge Ramon Vazquez Campero</center></h1>

**`| Exploratory Data Analysis | Variable Identification | Univariate Analysis | Bi-Variate Analysis | Advanced Python techniques |`**

As my first introduction to Data Science, this project not only deepened my understanding of data analytics but also ignited my passion for uncovering insights through data. Throughout this experience, I honed my skills in Exploratory Data Analysis, including Variable Identification, Univariate Analysis, and Bi-Variate Analysis, as well as advanced Python techniques. This accomplishment represents a pivotal step in my career journey, showcasing my ability to tackle complex data problems and deliver impactful solutions. I am excited to continue expanding my skill set and exploring new areas within data science. 🚀

<p align="left"> 
      <a href="https://www.linkedin.com/in/rayvazcari/">
         <img alt="Linkedin Profile" title="Likedin Profile" src="https://custom-icon-badges.demolab.com/badge/-Linkedin%20Profile-blue?style=for-the-badge&logoColor=white&logo=linkedin"/></a>
      </a>
</p>

---

### 🧰 Languages and Tools I Used on This Project
<img align="left" alt="Jupyter" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/jupyter/jupyter-original-wordmark.svg" />
<img align="left" alt="Maplotlib" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/matplotlib/matplotlib-original.svg" />
<img align="left" alt="Numpy" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/numpy/numpy-original.svg" />
<img align="left" alt="Pandas" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pandas/pandas-original.svg" />
<img align="left" alt="Plotly" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/plotly/plotly-original.svg" />
<img align="left" alt="Python" width="30px" style="padding-right:10px;"  src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" />
<img align="left" alt="VScode" width="30px" style="padding-right:10px;"  src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vscode/vscode-original.svg" />
<img align="left" alt="Seaborn" width="30px" style="padding-right:10px;" src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg"  /> 

<br />


---


<center><img src="https://brand.foodhub.com/images/png/logo_vertical_new.png" width="600" height="300"></center>

<br />

---

<a id='Problem-Statement'></a>
### Problem Statement 

#### Description

##### Context

The number of restaurants in New York is increasing day by day. Lots of students and busy professionals rely on those restaurants due to their hectic lifestyles. Online food delivery service is a great option for them. It provides them with good food from their favorite restaurants. A food aggregator company FoodHub offers access to multiple restaurants through a single smartphone app.

The app allows the restaurants to receive a direct online order from a customer. The app assigns a delivery person from the company to pick up the order after it is confirmed by the restaurant. The delivery person then uses the map to reach the restaurant and waits for the food package. Once the food package is handed over to the delivery person, he/she confirms the pick-up in the app and travels to the customer's location to deliver the food. The delivery person confirms the drop-off in the app after delivering the food package to the customer. The customer can rate the order in the app. The food aggregator earns money by collecting a fixed margin of the delivery order from the restaurants.

#### Objective

The food aggregator company has stored the data of the different orders made by the registered customers in their online portal. They want to analyze the data to get a fair idea about the demand of different restaurants which will help them in enhancing their customer experience. Suppose you are hired as a Data Scientist in this company and the Data Science team has shared some of the key questions that need to be answered. Perform the data analysis to find answers to these questions that will help the company to improve the business. 

#### Data Description

The data contains the different data related to a food order. The detailed data dictionary is given below.

Data Dictionary:
- **order_id**: Unique ID of the order
- **customer_id**: ID of the customer who ordered the food
- **restaurant_name**: Name of the restaurant
- **cuisine_type**: Cuisine ordered by the customer
- **cost**: Cost of the order
- **day_of_the_week**: Indicates whether the order is placed on a weekday or weekend (The weekday is from Monday to Friday and the weekend is Saturday and Sunday)
- **rating**: Rating given by the customer out of 5
- **food_preparation_time**: Time (in minutes) taken by the restaurant to prepare the food. This is calculated by taking the difference between the timestamps of the restaurant's order confirmation and the delivery person's pick-up confirmation.
- **delivery_time**: Time (in minutes) taken by the delivery person to deliver the food package. This is calculated by taking the difference between the timestamps of the delivery person's pick-up confirmation and drop-off information.

<br />

---

### Conclusion and Recommendations

### What are your conclusions from the analysis? What recommendations would you like to share to help improve the business?

### Conclusions:

1) Order and Delivery Patterns:

    - A significant portion of orders cost less than `$20`, with 29.24% of orders costing more than `$20`.
    - The mean order delivery time is approximately 24.16 minutes.
    - Delivery times vary significantly between weekdays and weekends, with mean delivery times of 28.34 minutes on weekdays and 22.47 minutes on weekends.

2) Customer Behavior:

    - The most frequent customers placed between 9 to 13 orders, indicating a high level of loyalty among a subset of the customer base.
    - Shake Shack, The Meatball Shop, Blue Ribbon Sushi, and Blue Ribbon Fried Chicken were identified as the top restaurants based on the number of orders received.
    - American cuisine is the most popular cuisine on weekends, showing strong customer preference during this period.

3) Operational Efficiency:

    - Higher-rated restaurants tend to spend more time preparing food, indicating a slight positive correlation between preparation time and ratings.
    - There is no clear relationship between delivery time and ratings, suggesting that factors other than speed and price influence customer satisfaction which is not expected at face value.

4) Revenue Insights:

    - The total net revenue generated by the company was `$6,166.30`, with a majority coming from orders costing more than `$20`.
    - Four restaurants (Shake Shack, The Meatball Shop, Blue Ribbon Sushi, and Blue Ribbon Fried Chicken) qualify for promotional offers based on their high rating counts and average ratings.

5) Cuisine Type:

    - American cuisine is the most popular on weekends, reflecting a strong customer preference.
    - Higher-rated cuisines, such as American and Japanese, generally have longer preparation times but result in higher customer satisfaction.
    - Certain cuisines, like Korean and Mediterranean, show higher variability in order costs, indicating a diverse range of offerings and price points.

6) Feedback Ratings:

    - Higher-rated orders tend to have longer preparation times, suggesting that quality and attention to detail contribute to customer satisfaction.
    - There is no clear relationship between delivery time and ratings, indicating that factors like food quality and service are more important for customer satisfaction.

7) Missing Ratings:

    - One of the most controversial aspects of this analysis was the amount of orders that did not have a rating. 
    - During the analysis, it was heavily debated what to do with the missing ratings, ultimately, it was decided that since it was a large percentage of the data, we would keep those missing values and continue the data analysis as it was except for data and analysis specific to ratings.
  
<br />

---

### Recommendations:

1) Operational Recomendations:

    - Improve delivery efficiency, particularly on weekdays, by optimizing delivery routes to reduce travel time.

2) Marketing and Promotions:

    - Continue offering promotional discounts to top-performing restaurants such as Shake Shack, The Meatball Shop, Blue Ribbon Sushi, and Blue Ribbon Fried Chicken to attract more customers.
    - Implement weekend specials focused on popular cuisines like American to boost sales further as majority of the sales are on Weekends.
    - Develop special offers for high-rated cuisines like American and Japanese to leverage their high customer satisfaction and boost revenue.
    
3) Customer Experience Recomendations:

    - Enhance communication with customers regarding expected delivery times, especially during peak hours or adverse traffic conditions, to manage expectations and reduce dissatisfaction.
    - Implement a robust feedback system to gather more detailed insights into customer preferences and pain points, enabling continuous improvement in service quality. A reward program dependent on wether you are rating your orders may be a good strategy and encourage customers to rate their orders more so there is not a lot of missing values that could affect the data. 
    
4) Revenue Growth Recomendations:

    - Continue developing loyalty programs targeting and rewarding frequent customers to encourage repeat orders and increase customer retention.
    - Take advantage of the weekends and the most popular food cuisines to boost revenue. 
    
5) Data-Driven Decisions:

    - Continue conducting regular data analysis to monitor trends in order volumes, delivery times, and customer satisfaction. This will help the company stay agile and responsive to changing customer needs and market conditions.
    - Invest in advanced analytics and machine learning tools to gain deeper insights into customer behavior, operational efficiency, and market trends.
