📊 Streaming Watchtime Analysis
Welcome to the Streaming Watchtime Analysis project!  
This project focuses on exploring how users interact with a streaming platform — what they watch, how long they watch, and from where — to discover patterns that can help improve user satisfaction and reduce churn.
---
🎯 Objective
The main goal of this project is to perform Exploratory Data Analysis (EDA) on a streaming dataset to answer key business questions like:
🎥 What kind of content do users prefer? (Movies or TV Shows, Comedy or Drama)
⏱️ How much time do they spend watching content?
📈 Which content is the most popular?
📱 What devices are they using? (Mobile, Laptop, Smart TV)
🌍 From which locations are users streaming?
📉 Are there any patterns that indicate user drop-off or low engagement?
---
🛠️ Tools & Libraries Used
The analysis was done using Python and the following libraries:
`pandas`, `numpy` – for data loading and manipulation
`matplotlib`, `seaborn`, `plotly` – for creating detailed and interactive visualizations
`ydata_profiling` – to generate a quick and automated profiling report
`warnings` – to suppress unnecessary output and keep the notebook clean
---
📂 Dataset Overview
The dataset contains detailed records of user watchtime behavior, including:
Content types (Movies, Shows)
Watch duration
User location
Device used for streaming
Content genres and names
📥 The dataset was loaded using `pandas.read_csv()` and initially inspected with `.head()`, `.info()`, and `.describe()` functions.
---
🔍 Key Steps in the Analysis
Data Cleaning 🧹
Checked for missing values, data types, and duplicates
Performed necessary preprocessing for analysis
Univariate Analysis 📊
Analyzed individual columns like content type, devices, locations, and watchtime
Bivariate Analysis 📈
Compared variables like device vs. content type, genre vs. watchtime, etc.
Visualizations 🖼️
Used bar charts, pie charts, heatmaps, and interactive plots with `plotly` to understand data patterns
Insights Generation 💡
Derived actionable insights about user preferences and behavior
---
✅ Outcomes
👁️ Identified the most watched content types and genres
📍 Tracked popular streaming locations and devices
⏰ Measured average and total watchtime
📊 Highlighted user engagement trends
💼 These insights can help the company improve its content strategy and enhance user experience
---
**📌 Conclusion
This project provides valuable business insights into user streaming habits and preferences.  
It helps stakeholders make data**
