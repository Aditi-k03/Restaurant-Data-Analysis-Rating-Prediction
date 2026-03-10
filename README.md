<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
</head>

<body>

<h1 align="center">🍽 Restaurant Data Analysis & Rating Prediction</h1>
<p align="center"><i>Data Science Internship Project – Cognifyz Technologies</i></p>

---

<h2>📄 Project Description</h2>

<p>
This project was completed during my Data Science Internship at Cognifyz Technologies. 
The aim of the project is to perform exploratory data analysis (EDA) on a large restaurant dataset 
and develop machine learning models to predict restaurant ratings.

The dataset includes information such as cuisines, location, price range, table booking availability,
online delivery services, and customer votes. Through data cleaning, visualization, and modeling,
the project identifies key factors influencing restaurant ratings.
</p>

---

<h2>🎯 Project Goals</h2>

<ul>
<li>🔍 Perform Exploratory Data Analysis (EDA) on restaurant dataset.</li>
<li>📊 Identify patterns influencing restaurant ratings.</li>
<li>📈 Build predictive models to estimate restaurant ratings.</li>
<li>📌 Apply feature engineering to improve model performance.</li>
<li>🧠 Evaluate different machine learning algorithms.</li>
</ul>

---

<h2>📊 Key Analysis Sections</h2>

<ul>

<li>📍 <b>Restaurant Distribution Analysis</b>
<ul>
<li>Identify cities with the highest number of restaurants.</li>
<li>Analyze geographic distribution of restaurants.</li>
<li>**New Delhi** has the highest number of restaurants.</li>
<li>Followed by **Gurgaon** and **Noida**.</li>

This shows that restaurant density is highly concentrated in metropolitan areas.
</ul>
</li>

<li>🍜 <b>Cuisine Analysis</b>
<ul>
<li>Most popular cuisines across locations.</li>
<li>Relationship between cuisine type and ratings.</li>
</ul>
</li>

<li>💰 <b>Price Range Analysis</b>
<ul>
<li>Effect of price range on customer ratings.</li>
<li>Price distribution among restaurants.</li>
<li>Higher priced restaurants tend to have **better ratings**.</li>

| Price Range | Average Rating |
|-------------|---------------|
| Budget | 3.24 |
| Mid Range | 3.38 |
| Premium | 3.78 |
| Luxury | 3.89 |

This indicates that restaurants with **higher investment and premium service quality generally achieve better customer satisfaction.**

</ul>
</li>

<li>⭐ <b>Rating Distribution Analysis</b>
<ul>
<li>Distribution of aggregate ratings.</li>
<li>Identification of rating patterns.</li>
</ul>
</li>

<li>📦 <b>Feature Engineering</b>
<ul>

Several new features were created to improve model performance:

- **Cuisine Count** → Number of cuisines served by a restaurant
- **High Rating Flag** → Binary indicator for highly rated restaurants
- **Multi-Cuisine Indicator** → Identifies restaurants serving multiple cuisines
- **Locality Name Length** → Used as a proxy for area complexity

Strongest correlated feature:

**Price Range → Correlation = 0.44**

Other useful predictors include:

- Number of Votes
- Cuisine Diversity
- Service Availability
<li>Impact of online delivery on ratings.</li>
<li>Impact of table booking availability.</li>
</ul>
</li>

</ul>

---

<h2>🤖 Machine Learning Models</h2>

Three regression models were evaluated:

| Model | MAE | RMSE | R² |
|------|------|------|------|
| Linear Regression | 0.399 | 0.503 | **0.183** |
| Decision Tree | 0.402 | 0.515 | 0.142 |
| Random Forest | 0.418 | 0.533 | 0.083 |

### 🏆 Best Model

✅ **Linear Regression**

Random Forest showed **overfitting**, where training performance was high but generalization on unseen data was poor.


<p>
Model performance was evaluated using:
</p>

<ul>
<li>MAE (Mean Absolute Error)</li>
<li>RMSE (Root Mean Square Error)</li>
<li>R² Score</li>
</ul>

---

<h2>📈 Key Insights</h2>

<ul>
<li>Restaurants with higher price ranges tend to have better ratings.</li>
<li>Table booking availability positively influences ratings.</li>
<li>Customer votes are strongly correlated with rating reliability.</li>
<li>Location alone has a weak correlation with ratings.</li>
</ul>

---

<h2>🛠 Tools & Technologies</h2>

<ul>
<li>Python</li>
<li>Pandas</li>
<li>NumPy</li>
<li>Matplotlib</li>
<li>Seaborn</li>
<li>Scikit-Learn</li>
<li>Jupyter Notebook</li>
</ul>

---

<h2>📁 Dataset Details</h2>

<ul>
<li>Dataset Size: ~9551 Restaurants</li>
<li>Features: 21 columns</li>
<li>Countries Covered: 15</li>
<li>Target Variable: Aggregate Rating</li>
</ul>

Important dataset attributes include:

- Restaurant Name
- City
- Latitude & Longitude
- Cuisines
- Price Range
- Online Delivery
- Table Booking
- Votes
- Aggregate Rating
  
---

<h2>🌍 Real-World Applications</h2>

<ul>
<li>Restaurant businesses can analyze customer preferences.</li>
<li>Food delivery platforms can recommend highly rated restaurants.</li>
<li>Investors can identify profitable restaurant locations.</li>
<li>Data scientists can build recommendation systems.</li>
</ul>

---

<h2>📌 Conclusion</h2>

<p>
This project demonstrates the complete data science workflow, including data cleaning,
exploratory data analysis, feature engineering, and predictive modeling.
The findings highlight the importance of price range, service availability,
and customer engagement in determining restaurant ratings.
</p>

---

<h2>👩‍💻 Author</h2>

<ul>
<li><b>Aditi Ganpat Khade</b></li>
<li>Data Science Intern – Cognifyz Technologies</li>
<li>📧 Email: aditi.khade99@gmail.com</li>
<li>💼 LinkedIn: <a href="https://www.linkedin.com/in/aditi-khade-2a69bb274/">LinkedIn Profile</a></li>
</ul>

</body>
</html>
