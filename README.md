# 📊 Bellabeat Case Study: Data-Driven Insights  
## 🏆 Case Study Objective  
Bellabeat, a high-tech manufacturer of health-focused products for women, aims to expand its market.  
This analysis explores *how activity, sleep, heart rate, and weight impact calorie burn* to guide Bellabeat’s marketing strategy.  

---

## 📂 Datasets Used  
✔ dailyActivity_merged.csv – Steps, activity intensity, calories burned.  
✔ sleepDay_merged.csv – Sleep duration and quality.  
✔ heartrate_seconds_merged.csv – Heart rate levels over time.  
✔ hourlyIntensities_merged.csv – Activity intensity.  
✔ weightLoginfo_merged.csv – Weight, BMI, and fat percentage.  

---

## 🔎📊 Updated Key Findings 

1️⃣ Higher Activity Levels Lead to More Calories Burned
✔ Users with 400+ daily intensity points burn an average of 3,200 calories/day, while those with under 200 points burn below 2,200 calories/day.
✔ The strongest correlation (0.72) was found between Very Active Minutes and Calories Burned.

2️⃣ Daily Steps and Calories Burned Show a Moderate Relationship
✔ Users walking 10,000–15,000 steps/day burn approximately 2,500–3,500 calories/day.
✔ However, step count alone has a weaker correlation (0.48) compared to intensity and duration of activity.

3️⃣ Weight Alone Does Not Strongly Impact Calorie Burn
✔ Some users weighing 85+ kg burned over 3,500 calories, while others at the same weight burned under 2,000 calories.
✔ The correlation between weight and calories burned is only 0.37, proving that activity level matters more than weight itself.

4️⃣ Activity Levels Are Not Evenly Distributed
✔ 67% of users recorded less than 5 minutes of very active time per day.
✔ Only 10% of users engaged in 30+ minutes of high-intensity activity, suggesting low engagement in intense workouts.

5️⃣ Calorie Burn Distribution Shows a Right Skew
✔ The median calorie burn is 2,700 calories/day, but top 5% of users exceeded 4,000 calories due to intense workouts.
✔ This variation highlights individual differences in metabolism and activity habits.

🔹 Overall Recommendation:  “Bellabeat should introduce an ‘Active Minutes Goal’ feature in the Bellabeat app to motivate users. This feature can provide real-time intensity tracking and personalized workout challenges, encouraging users to stay active longer.”


## 📊 Visualizations  
The analysis includes:  
✔ Scatter plots (Activity Intensity vs. Calories Burned, Weight vs. Calories Burned).  
✔ Bar charts (Activity Levels Breakdown).  
✔ Histograms (Calories Burned Distribution).  

## 📊 Charts Description 

📊 1. Activity Levels Breakdown

✔ Chart Title: Breakdown of Activity Levels
✔ Description: This bar chart categorizes users into Sedentary, Lightly Active, Fairly Active, and Very Active groups.
✔ Key Insights:
	•	67% of users spend less than 5 minutes/day in high-intensity activities.
	•	The majority of users fall into Lightly Active (43%) and Sedentary (35%) categories.
	•	Bellabeat should encourage higher intensity workouts to improve user fitness.

📊 2. Activity vs. Calories Burned

✔ Chart Title: Relationship Between Activity Intensity and Calories Burned
✔ Description: A scatter plot showing how activity intensity affects calorie expenditure.
✔ Key Insights:
	•	Users with 400+ Very Active Minutes burn an average of 2,500+ calories.
	•	Correlation = 0.72, proving intensity is a key driver of calorie burn.
	•	Bellabeat should market intensity-based workouts instead of step count alone.

📊 3. Calories Burned Distribution

✔ Chart Title: Distribution of Calories Burned
✔ Description: A histogram showing how calorie burn varies across users.
✔ Key Insights:
	•	Most users burn between 2,000 and 3,000 calories/day.
	•	Only 5% of users exceed 4,000 calories/day, indicating intense workouts.
	•	Bellabeat can use personalized coaching to push lower-calorie burners towards higher activity levels.

📊 4. Steps vs. Calories Burned

✔ Chart Title: Daily Steps vs. Calories Burned
✔ Description: This scatter plot explores the link between steps taken per day and calories burned.
✔ Key Insights:
	•	Users taking 12,000+ steps/day burn ~3,000 calories.
	•	Correlation (0.48) is weaker than activity intensity (0.72), proving intensity matters more than just step count.
	•	Adding step challenges may increase movement, but intensity should be Bellabeat’s marketing focus.

📊 5. Daily Intensity Boxplot

✔ Chart Title: Boxplot of Daily Intensity Levels
✔ Description: This boxplot visualizes the distribution of Daily Intensity levels.
✔ Key Insights:
	•	50% of users have an intensity score below 300, meaning they engage in low/moderate exercise only.
	•	Outliers exist with intensity scores exceeding 600, indicating a small but highly active group.
	•	Personalized coaching can help low-intensity users reach higher fitness levels.

📊 6. Weight vs. Calories Burned

✔ Chart Title: Weight vs. Calories Burned
✔ Description: This scatter plot examines the relationship between weight and calorie expenditure.
✔ Key Insights:
	•	A weak correlation (0.37) suggests weight alone is NOT a major factor in calorie burn.
	•	Users with higher weight (85+ kg) burned both high and low calories, depending on activity level.
	•	Activity level is a better predictor of calorie burn than weight.

🔹 Check the *[PowerPoint Presentation](./Bellabeat_Analysis_Presentation.pptx)* for insights.  
🔹 See the *[HTML Report](./Bellabeat_Case_Study.html)* for the full analysis.

---

## 🎯 Business Recommendations  
✔ *1. Market “Active Minutes” Instead of Step Goals*  
✔ *2. Introduce a “Heart Rate Efficiency Score”*  
✔ *3. Expand Sleep & Recovery Coaching*  
✔ *4. Develop Personalized Calorie Burn Predictions*  

---

## ⚙ Files in This Repository  
📌 Bellabeat_Case_Study.Rmd – R Markdown analysis.  
📌 Bellabeat_Case_Study.html – Interactive report.  
📌 Bellabeat_Analysis_Presentation.pptx – PowerPoint summary.  
📌 merged_data.csv – Cleaned dataset for future use.  

---

## 🚀 Next Steps  
🔹 Implement personalized health coaching in Bellabeat products.  
🔹 Optimize marketing based on activity intensity insights.  
🔹 Explore *hydration, stress tracking, and nutrition data* for further research.

---

## 📌 About  
🎯 *Author:* James Vinyo  
📅 *Last Updated:* February 18, 2025  

📩 *Contact:* 
Email: harryjamesmethod@outlook.com

LinkedIn: https://www.linkedin.com/in/james-vinyo-6860b9335?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app
