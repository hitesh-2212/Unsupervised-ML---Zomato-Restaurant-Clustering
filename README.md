<h1 align="center">🍽️ Zomato Restaurant Analysis & Clustering</h1>
<p align="center">
  <b>Customer Sentiment Analysis | Restaurant Segmentation | Business Analytics</b>
</p>

<hr>

<h2>🏢 Business Context</h2>
<p>
<b>Zomato</b> is an Indian restaurant aggregator and food delivery platform founded in 2008.
It provides restaurant listings, menus, user reviews, ratings, and food delivery services
across multiple Indian cities.
</p>

<p>
India’s restaurant industry is highly diverse, driven by <b>regional cuisines, pricing
variations, and customer preferences</b>. With a rapidly growing number of restaurants
and increasing adoption of online food delivery, both customers and businesses require
<b>data-driven insights</b> to make informed decisions.
</p>

<p>
This project analyzes Zomato’s restaurant and review data across Indian cities to uncover
<b>customer sentiment, pricing patterns, cuisine trends, and restaurant segments</b>.
The goal is to support better restaurant discovery for customers and strategic
decision-making for Zomato and restaurant owners.
</p>

<hr>

<h2>🎯 Project Objectives</h2>
<ul>
  <li>Analyze <b>customer sentiments</b> from restaurant reviews</li>
  <li>Identify patterns related to <b>cuisine, cost, and ratings</b></li>
  <li>Cluster restaurants into <b>meaningful segments</b> using unsupervised learning</li>
  <li>Support customers in finding the <b>best restaurants in their locality</b></li>
  <li>Help Zomato and restaurant owners identify <b>strengths and improvement areas</b></li>
</ul>

<hr>

<h2>📊 Dataset Description</h2>
<p>
The dataset contains restaurant-level and customer review data sourced from Zomato,
covering multiple cities in India.
</p>

<ul>
  <li><b>Restaurant Name & City</b></li>
  <li><b>Average Cost for Two</b></li>
  <li><b>Aggregate Rating</b></li>
  <li><b>Total Reviews</b></li>
  <li><b>Cuisine Types</b></li>
  <li><b>Online Delivery & Table Booking</b></li>
  <li><b>Customer Reviews & Metadata</b></li>
</ul>

<hr>

<h2>🛠️ Tools & Techniques</h2>
<ul>
  <li><b>Python:</b> Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn</li>
  <li><b>Exploratory Data Analysis (EDA)</b></li>
  <li><b>Text-based Sentiment Analysis</b></li>
  <li><b>Feature Scaling & Transformation</b></li>
  <li><b>Clustering Algorithms:</b> K-Means, Hierarchical Clustering</li>
  <li><b>Cluster Validation:</b> Silhouette Score</li>
</ul>

<hr>

<h2>🤖 Clustering Approach</h2>
<p>
Restaurants were clustered using features such as:
</p>

<ul>
  <li>Average Cost</li>
  <li>Aggregate Rating</li>
  <li>Total Reviews</li>
  <li>Cuisine Count</li>
</ul>

<p>
Both <b>K-Means</b> and <b>Hierarchical Clustering</b> were applied to compare
segmentation consistency and interpretability.
</p>

<hr>

<h2>📈 Model Evaluation</h2>
<p>
The clustering model achieved a <b>Silhouette Score of ~0.30</b>.
</p>

<h3>❓ Why a Silhouette Score of 0.30 is Acceptable</h3>
<ul>
  <li>Restaurant data is <b>naturally overlapping</b> (pricing, ratings, and cuisines often intersect)</li>
  <li>Customer preferences are subjective, making <b>perfect separation unrealistic</b></li>
  <li>In real-world business datasets, scores between <b>0.25–0.40</b> often indicate
      <b>meaningful and usable clusters</b></li>
  <li>Clusters showed <b>clear business interpretation</b> (premium, budget, low-engagement restaurants)</li>
</ul>

<p>
📌 <i>Interpretability and business value were prioritized over artificially maximizing the metric.</i>
</p>

<hr>

<h2>🔍 Key Insights</h2>
<ul>
  <li>High-cost restaurants generally receive <b>higher ratings</b> but fewer reviews</li>
  <li>Budget restaurants attract <b>more reviews</b> with moderate ratings</li>
  <li>Cuisine diversity positively impacts customer engagement</li>
  <li>Sentiment analysis reveals that <b>service and consistency</b> matter more than price alone</li>
  <li>Distinct restaurant segments help explain differences in performance and popularity</li>
</ul>

<hr>

<h2>💼 Business Value for Stakeholders</h2>

<h3>👥 Customers</h3>
<ul>
  <li>Easier discovery of <b>best restaurants by price, rating, and cuisine</b></li>
  <li>Improved dining decisions based on <b>sentiment and review trends</b></li>
</ul>

<h3>🏪 Restaurant Owners</h3>
<ul>
  <li>Understand their <b>competitive segment</b></li>
  <li>Identify areas where they lag (pricing, ratings, customer sentiment)</li>
  <li>Benchmark performance against similar restaurants</li>
</ul>

<h3>🏢 Zomato (Company)</h3>
<ul>
  <li>Enable <b>personalized restaurant recommendations</b></li>
  <li>Support data-driven onboarding and promotion strategies</li>
  <li>Identify high-potential restaurants and underperforming segments</li>
</ul>

<hr>

<h2>🚀 Conclusion</h2>
<p>
This project demonstrates how <b>clustering and sentiment analysis</b> can convert
raw restaurant data into actionable insights. Despite moderate silhouette scores,
the clusters provide <b>clear business value</b>, supporting better decision-making
for customers, restaurants, and the Zomato platform.
</p>

<hr>

<p align="center">
  <i>📌 This project showcases real-world analytics where business interpretability
  matters more than perfect metrics.</i>
</p>
