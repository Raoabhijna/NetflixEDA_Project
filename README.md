## 🏷️Overview:

Netflix is the world’s leading subscription-based streaming platform, offering a vast collection of movies, TV series, documentaries, and original content to over 200 million users across more than 190 countries. Known for revolutionizing the way people consume media, Netflix has shifted its strategy over the years to prioritize original and region-specific content to retain and grow its subscriber base.
This project presents a comprehensive Exploratory Data Analysis (EDA) of the Netflix content catalog as of 2019. The dataset, sourced from Flixable (a third-party Netflix search engine), includes information about each title’s type (movie or TV show), country of availability, release year, cast, directors, and more.
The goal of the project is to understand how Netflix has evolved its content strategy, including the growing emphasis on TV shows over movies, the distribution of content across different countries, and trends in content production over the years. It also includes a UMB (User-Movie-Behavior) rule analysis to simulate how users might interact with different types of content and identify patterns that could influence recommendation systems.
By uncovering these insights, the project not only highlights Netflix’s global strategy and content shifts but also demonstrates how data-driven analysis can inform strategic decision-making in digital media platforms.

## 🎯 Business Objective
The objective is to extract **actionable insights** that address:
- 📺 What types of content dominate Netflix?
- 🌍 How is content distributed across different countries?
- 📈 Has there been a shift from movies to TV shows over time?
- 🧠 What behavioral patterns emerge using UMB (User-Movie-Behavior) rules?
These insights can drive smarter decisions around content acquisition, personalization, and market-specific strategies.


## 🧹 Data Preprocessing Highlights

- Removed duplicates and null values.
- Split and exploded multi-valued columns (e.g., genres, cast).
- Converted dates into appropriate datetime formats.
- Extracted useful features like `year_added`, `runtime_in_mins`, `no_of_seasons`.

## 📊 Key Analysis & Visualizations

### 🔢 Content Distribution

- Count plots showing the proportion of Movies vs TV Shows
- Temporal trends highlighting Netflix’s increased production from 2015 to 2019

### 🌍 Country-wise Analysis

- Bar plots of top 10 countries by number of titles
- Insight into how countries like the U.S., India, and the UK dominate the catalog

### 🔄 Movie vs TV Show Shift Over Time

- Line charts showing release year-wise content production shift
- Evidence of growing emphasis on serialized TV content post-2018

### 🎭 Genre & Ratings Analysis

- Genre popularity by content type
- Duration vs Rating boxplots
- Rating frequency distribution — showcasing the dominance of TV-MA, TV-14

## 📌 Findings

- **TV Shows are gaining traction**, particularly after 2018.
- **Content diversity is high**, with genres like Drama, Comedy, and International TV dominating.
- **US, India, and UK** lead in title count, reflecting major markets.
- **Mature-rated content** (TV-MA) is the most prevalent.
- **Genre preferences vary by type**, helping tailor recommendations and regional strategies.

## 🧾 Conclusion

This project provides valuable insights into Netflix's evolving content strategy and global catalog distribution. Through exploratory data analysis, we observed a clear shift from movies to TV shows over recent years, reflecting changing viewer preferences and strategic business decisions. Analyzing content by country revealed regional differences in content types and potential opportunities for localized offerings. By integrating external ratings data, Netflix can also focus on content quality. These findings empower the client to make data-driven decisions to enhance user satisfaction, retention, and market-specific content strategies.
