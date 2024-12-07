# MovieLens Data Exploration
## About the Project
This project uses the MovieLens dataset, which contains anonymous movie ratings and user demographic information. The dataset is designed to help explore patterns in movie preferences and user behavior. It includes data cleaning, visualization, and insights into how demographics like age and gender influence ratings. Python libraries like Pandas, Seaborn, and Matplotlib were used to analyze and visualize the data.

## Dataset Overview
- Contains 1,000,209 ratings for around 3,900 movies from 6,040 users.
- Ratings are on a 1-5 star scale.
- Includes demographic details like gender, age, and occupation for users who provided them voluntarily.

## File Descriptions
### 1. Ratings File (`ratings.dat`)
- Format: `UserID::MovieID::Rating::Timestamp`
- Each user has at least 20 ratings.
- `Timestamp` shows when the rating was made (in seconds since the epoch).
  
### 2. Users File (`users.dat`)
- Format: `UserID::Gender::Age::Occupation::Zip-code`
- Gender: "M" (Male) or "F" (Female).
- Age groups:
    - 1: Under 18
    - 18: 18-24
    - 25: 25-34
    - 35: 35-44
    - 45: 45-49
    - 50: 50-55
    - 56: 56+
- Occupations include categories like student, educator, engineer, and more.

### 3. Movies File (`movies.dat`)
- Format: `MovieID::Title::Genres`
- Genres are pipe-separated and include categories like Comedy, Drama, Sci-Fi, etc.

## Key Features
- The dataset provides a rich source of information for exploring user preferences, collaborative filtering, and recommender systems.
- Ideal for learning data analysis, data visualization, and machine learning.

## Usage Notes
- This dataset is for educational and research purposes only.
- Ratings and demographic information are provided as-is and may contain errors or inconsistencies.
