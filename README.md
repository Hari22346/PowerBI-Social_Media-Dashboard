# PowerBI-Social_Media-Dashboard

# 📊 Social Media Analytics Dashboard – Understanding Your Audience

## 📌 Project Overview

**Social Media Analytics – Understanding Your Audience** is an interactive **Power BI dashboard** developed to analyze social media engagement, audience demographics, video performance, hobbies, professions, and geographical trends.

The project transforms raw social media data into meaningful visual insights using **Power BI, data cleaning, aggregation, filtering, and interactive dashboards**.

The dashboard allows users to understand:

- 👥 Audience demographics
- 👍 Likes, comments and shares
- 🎥 Video-view performance
- 🎯 User interests and hobbies
- 💼 Profession-wise engagement
- 🌍 Country-wise social media activity
- 📈 Age and gender distribution

---

## 🎯 Objectives

The main objectives of this project are:

1. Analyze overall social media engagement.
2. Understand audience behavior based on gender and age.
3. Identify engagement patterns across different hobbies.
4. Compare video views across professions.
5. Analyze social media activity across countries.
6. Build an interactive dashboard using Power BI.
7. Provide an easy-to-understand visual representation of social media data.
8. Generate actionable insights from raw user engagement data.

---

## 🗂️ Dataset

The project uses a social media dataset containing **200 user records** and **11 attributes**.

### Dataset Columns

| Column | Description |
|---|---|
| `user_id` | Unique user identifier |
| `country` | User's country |
| `gender` | User gender |
| `age` | User age |
| `likes` | Number of likes |
| `comments` | Number of comments |
| `shares` | Number of shares |
| `profession` | User profession |
| `hobby` | User hobby |
| `3-second-video-views` | Number of 3-second video views |
| `1-minute-video-views` | Number of 1-minute video views |

---

## 📊 Key Metrics

The overall dashboard provides the following major KPIs:

| KPI | Total |
|---|---:|
| 👍 Total Likes | **487,797** |
| 🔄 Total Shares | **198,611** |
| 💬 Total Comments | **96,340** |
| 👁️ 3-Second Video Views | **984,655** |
| 🎥 1-Minute Video Views | **501,233** |
| 👥 Total Users | **200** |
| 🌍 Countries | **10** |
| 💼 Professions | **10** |
| 🎯 Hobbies | **10** |

> KPI values are calculated from the complete dataset and may appear rounded in the Power BI dashboard using K-formatting.

---

# 📈 Dashboard Features

## 1. Overall Dashboard

The main dashboard provides a complete overview of social media performance.

### Main KPIs

- Total Likes
- Total Shares
- Total Comments
- Total 3-second Video Views
- Total 1-minute Video Views

### Visualizations

- Likes, shares and comments by hobby
- Video views by profession
- Likes by gender
- Age distribution by gender
- Country-wise social media engagement

![Overall Dashboard](""C:\Users\a\OneDrive\Pictures\social_media_analyis.screenshots\Overall.png"")

---

## 2. Gender Analysis

The dashboard provides interactive analysis for:

- Female users
- Male users
- Non-binary users

The gender filter dynamically updates all dashboard visuals.

### Gender-wise Analysis Includes

- Total likes
- Total shares
- Total comments
- Video views
- Hobby engagement
- Profession-wise video views
- Age distribution
- Country-wise engagement

![Female Analysis](Female.png)

![Male Analysis](Male.png)

![Non-Binary Analysis](Non_binary.png)

---

## 3. Hobby-wise Analysis

The dashboard analyzes engagement based on user hobbies.

Example hobbies available in the dataset include:

- Traveling
- Gaming
- Music
- Dancing
- Sports
- Cycling
- Reading
- Photography
- Painting
- Cooking

The dashboard compares:

**Likes + Shares + Comments by Hobby**

This helps identify how different interest groups interact with social media content.

![Hobby Analysis](overall_hobby_wise.png)

---

## 4. Profession-wise Analysis

The dashboard analyzes video engagement across different professions.

Examples include:

- Developer
- Scientist
- Designer
- Teacher
- Doctor
- Entrepreneur
- Musician
- Artist
- Writer
- Engineer

The visualization compares:

- 3-second video views
- 1-minute video views
- Likes

This helps understand how audience engagement varies across professional groups.

![Profession Analysis](overall_proffesion_wise.png)

---

## 5. Country-wise Analysis 🌍

The dashboard contains an interactive geographical visualization showing social media engagement across countries.

The country filter can be used to analyze individual markets.

For example, selecting **India** updates the dashboard to show India-specific:

- Likes
- Shares
- Comments
- Video views
- Age distribution
- Gender engagement
- Hobby engagement
- Profession engagement

![Country Analysis](overall_country_wise.png)

---

# 🔍 Interactive Filters

The Power BI dashboard contains multiple slicers that allow users to dynamically explore the dataset.

### Available Filters

- **Gender**
- **Hobby**
- **Profession**
- **Country**

These filters interact with the dashboard visuals and allow users to perform detailed audience segmentation.

---

# 🧠 Data Analysis Performed

The project includes the following analytical processes:

### Data Cleaning

- Checked dataset structure
- Verified column types
- Checked missing values
- Prepared categorical and numerical fields
- Prepared data for Power BI visualization

### Exploratory Data Analysis

Analyzed:

- Engagement metrics
- Audience demographics
- Age distribution
- Gender distribution
- Hobby preferences
- Professional groups
- Country-wise engagement
- Video-view behavior

### Aggregation

Calculated:

- SUM of likes
- SUM of shares
- SUM of comments
- SUM of 3-second video views
- SUM of 1-minute video views
- COUNT of users

---

# 🛠️ Technologies Used

### Data Analysis

- Python
- Pandas
- NumPy

### Data Visualization

- Microsoft Power BI
- Power BI Maps
- Interactive Slicers
- KPI Cards
- Bar Charts
- Donut Charts
- Stacked Charts

### Data Source

- CSV Dataset

---

# 🏗️ Power BI Data Model

The project uses a Power BI data model containing the social media analysis dataset and its fields.

![Power BI Model](Model_view.png)

The model contains fields related to:

- User information
- Demographics
- Engagement
- Profession
- Hobby
- Country
- Video views

---

# 📊 Dashboard Pages / Analysis Views

The project demonstrates several analytical perspectives:

### Overall View

Provides a complete summary of social media engagement.

### Gender View

Analyzes audience engagement based on:

- Female
- Male
- Non-binary

### Hobby View

Compares engagement across different interests.

### Profession View

Analyzes video performance across professions.

### Country View

Provides geographical analysis and country-specific audience insights.

---

# 💡 Key Insights

Based on the complete dataset:

- The dataset contains **200 users**.
- The dataset records approximately **488K likes**.
- Users generated approximately **199K shares**.
- Total comments are approximately **96K**.
- 3-second video views are approximately **985K**.
- 1-minute video views are approximately **501K**.
- The dataset contains **10 countries**.
- The dataset contains **10 professions**.
- The dataset contains **10 hobbies**.
- The audience includes Female, Male and Non-binary users.
- Interactive filtering allows engagement patterns to be explored at demographic, professional, hobby and geographic levels.

---

# 📁 Project Structure

```text
Social-Media-Analytics/
│
├── 📊 Social_media.pbix
│
├── 📄 social_media_analysis.csv
│
├── 🖼️ Overall.png
├── 🖼️ Female.png
├── 🖼️ Male.png
├── 🖼️ Non_binary.png
├── 🖼️ Model_view.png
├── 🖼️ overall_country_wise.png
├── 🖼️ overall_hobby_wise.png
├── 🖼️ overall_proffesion_wise.png
│
└── 📄 README.md
