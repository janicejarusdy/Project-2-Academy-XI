🎬 New Movie Studio Recommendations


📌 Overview
This project provides strategic recommendations for Microsoft's potential entry into the movie industry. By analysing box office performance data, we uncover key insights into how seasonality, genre, and popularity metrics affect a movie’s commercial success. These findings aim to guide Microsoft in planning a successful debut release for its new movie studio.

❓ Business Problem
Microsoft is exploring expansion into the film industry but lacks industry-specific knowledge. This project addresses the question:

What factors contribute to a movie's box office success, and how can Microsoft leverage these to launch a successful first film?

📊 Data Sources
The Numbers: Release date, production budget, gross earnings

Box Office Mojo: Studio, domestic and foreign gross

Rotten Tomatoes (Info & Reviews): Genre, ratings, reviews, runtime, etc.

TheMovieDB & IMDb: Popularity metrics and critic/audience scores

🔍 Methodology
Data Cleaning and Integration from multiple sources

Exploratory Data Analysis (EDA)

Correlation and regression analysis

Visualisation using Matplotlib and Seaborn

✅ Key Findings
Seasonality: Movies released in May–July perform significantly better.

Genres: Action, adventure, and animation are the top-performing genres.

Popularity: IMDb ratings and social media popularity show strong correlation with higher box office returns.

💡 Recommendations
Target May–July for first movie release

Focus on high-performing genres

Invest in production budget and marketing to boost popularity before release

📁 Project Structure
bash
Copy
Edit
├── dsc-phase2-project-final.ipynb  # Main notebook
├── data/                           # Raw and cleaned datasets
├── visuals/                        # Generated plots and charts
└── README.md                       # Project documentation
🛠️ Tech Stack
Python (Pandas, NumPy, Matplotlib, Seaborn)

Jupyter Notebook

Data sourced from public APIs and box office datasets

📈 Next Steps
Develop a predictive model for revenue estimation

Conduct A/B testing for marketing strategies

Extend analysis to streaming trends post-COVID

--- 

Author: Janice Teguh
N.B.: Make sure to extract im.db file first inside Data folder before continuing with analysis, otherwise it will produce an error
