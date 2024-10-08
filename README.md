# Data-Analysis
Portfolio

# Fitbit Data Analysis: Activity, Sleep, and Calorie Burn Study

## Introduction

This project analyzes Fitbit user data to identify trends in physical activity, sleep patterns, and calorie expenditure. Our goal is to extract actionable insights that can help improve user engagement and promote healthier behavior. By examining correlations between active minutes, sleep, and calorie burn, we offer recommendations for optimized user experience and system performance.

## Dataset

The data used for this analysis is publicly available and contains multiple metrics including:

- **Activity**: Steps taken, calories burned, active minutes, and sedentary behavior.
- **Sleep**: Sleep duration and quality.
- **Weight**: User-recorded weight logs.

You can find the dataset [here on Kaggle](https://www.kaggle.com/datasets/arashnic/fitbit).

## Business Insights

From our analysis, we derived the following insights that can be valuable for Fitbit's user engagement strategies:

1. **Optimal Maintenance Time**: 
   - The majority of users are asleep at 4 AM, making this the ideal time for system maintenance or notifications to avoid disrupting user activity.

2. **Active Minutes Boost Calorie Burn**:
   - A strong correlation between active minutes and calories burned suggests that encouraging users to increase their active minutes can lead to higher calorie expenditure. Fitbit can leverage this by sending targeted activity reminders.

3. **High Sedentary Time**:
   - Users spend a significant portion of their day in sedentary minutes. Fitbit could introduce notifications to nudge users toward light activity after prolonged periods of inactivity.

4. **Sleep-Activity Balance**:
   - A slight correlation between sleep duration and active minutes implies that users who are more active may sleep longer. Promoting healthy sleep routines alongside physical activity could lead to improved user well-being.

5. **Encouraging Weight Logging**:
   - There is insufficient weight data in the dataset, which highlights the need for encouraging users to log their weight more consistently. Fitbit can promote the benefits of weight tracking through reminders and personalized insights.

6. **Consistent Calorie Burn**:
   - Users burn over 60 calories per hour, even during their most restful periods. This can help find the minimum calorie burn for a user, even if were no active minutes.


## Code

The entire data analysis and visualization were conducted in Python, utilizing libraries such as `pandas`, `matplotlib`, and `seaborn`. You can view and run the complete code here:

[Fitbit Data Analysis Google Colab notebook](https://colab.research.google.com/drive/1246f15GbOath4nxG3RoUxYP--2fcmrec?usp=sharing)
## Conclusion

This analysis provides valuable insights for Fitbit to enhance its user engagement through targeted notifications, balanced activity, and optimized system operations. By leveraging these insights, Fitbit can help users improve their daily activity levels, manage their weight more effectively, and maintain healthier routines.

