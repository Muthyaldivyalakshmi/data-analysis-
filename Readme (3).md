# 📱 Profitable App Profiles for App Store and Google Play  

📝 Project Overview
This project performs Exploratory Data Analysis (EDA) on mobile applications from the Google Play Store and Apple App Store datasets. The goal is to analyze app trends, ratings, pricing, and other factors to understand the mobile app market better.

🎯 Objectives
✔ Understand the distribution of apps in both stores.
✔ Analyze factors influencing app ratings, pricing, and installs.
✔ Identify key differences between Google Play Store and Apple App Store.
✔ Visualize trends using matplotlib and seaborn.

📂 Datasets Used
We analyzed two datasets:

1️⃣ Google Play Store Dataset (googleplaystore.csv)
Feature	Description
App	Name of the application
Category	App category (Game, Productivity, etc.)
Rating	Average rating (out of 5)
Reviews	Number of user reviews
Size	Size of the app (MB/Varies)
Installs	Number of installs
Type	Free or Paid
Price	Cost of the app ($)
Content Rating	Age suitability (Everyone, Teen, etc.)
Genres	Genres of the app
Last Updated	Last update date

2️⃣ Apple App Store Dataset (AppleStore.csv)
Feature	Description
track_name	App name
size_bytes	Size of the app (in bytes)
price	Price of the app ($)
rating_count_tot	Total number of user ratings
user_rating	Average rating (out of 5)
prime_genre	App category
is_paid	Free or Paid

🛠 Technologies & Libraries Used:

Python 🐍
Pandas 📊
Matplotlib 📈
Seaborn 🎨
Jupyter Notebook 📒

🔍 Data Cleaning & Preprocessing:

Before analysis, the datasets required cleaning:
✔ Converted Size to MB in the Google Play dataset.
✔ Replaced "Varies with device" with NaN values for size.
✔ Removed duplicates & missing values.
✔ Converted Installs and Price to numerical format.
✔ Created a new column is_paid (Free/Paid apps) in Apple dataset.

📊 Key Data Visualizations & Insights:

1️⃣ Top 10 Categories by Total Installs (Google Play Store)
🔹 Categories like Games, Communication, and Social have the highest installs.
🔹 Entertainment and Productivity apps also show high engagement.
🔹 Niche categories (e.g., Comics, Parenting) have significantly fewer installs.

2️⃣ App Rating vs. Number of Installs (Google Play Store)
🔹 Highly-rated apps (4.5+) tend to have more installs.
🔹 Some low-rated apps still get installs, indicating brand trust or necessity.

3️⃣ Distribution of App Ratings (Google Play Store)
🔹 Majority of apps have ratings between 4.0 and 4.5.
🔹 Very few apps have low ratings (<2.0), suggesting poor apps get removed.

4️⃣ Free vs. Paid Apps (Google Play Store)
🔹 90%+ of apps are free, confirming the dominance of ad-supported models.
🔹 Paid apps are a minority, often targeting niche audiences.

5️⃣ App Price vs. User Ratings (Apple App Store)
🔹 No clear link between app price and rating. Free apps perform just as well as paid ones.
🔹 Expensive apps ($50+) have fewer ratings, suggesting lower adoption.

6️⃣ App Size vs. User Ratings (Apple App Store)
🔹 Larger apps tend to have higher ratings, likely due to better graphics & features.
🔹 Smaller apps are common, but ratings vary widely.

7️⃣ Number of Apps per Category (Apple App Store)
🔹 Games dominate the App Store.
🔹 Other popular categories include Entertainment, Business, and Education.

8️⃣ Free vs. Paid Apps (Apple App Store)
🔹 Most apps are free, similar to Google Play.
🔹 Paid apps tend to be in niche categories like Health & Fitness, Business.

📌 Conclusion & Key Takeaways

✔ Google Play Store is dominated by free apps, with categories like Games & Social having the most installs.
✔ App ratings matter, as higher-rated apps tend to get more downloads.
✔ Paid apps are rare but exist in specialized categories.
✔ App size can influence user ratings, especially in Apple’s App Store.
✔ The business model (free vs. paid) is similar in both stores, but app distribution differs.

🚀 How to Run This Project?

1️⃣ Clone this repository:

git clone https://github.com/yourusername/mobile-app-eda.git

2️⃣ Install dependencies:

pip install pandas matplotlib seaborn jupyter

3️⃣ Open Jupyter Notebook:

jupyter notebook
4️⃣ Run EDA_Mobile_Apps.ipynb 📒

🔗 Future Enhancements

📌 Conduct sentiment analysis on app reviews.
📌 Use machine learning to predict app success.
📌 Build an interactive dashboard using Tableau or Power BI.

🏆 About Me

👋 Hi, I'm M. Divya Lakshmi, a data analyst passionate about exploring insights from real-world datasets.
💼 I specialize in data analysis, visualization, and business intelligence.
📩 Feel free to connect with me!
E-mail ID: muthyaldivyalakshmi@gmail.com