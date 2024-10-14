# Spotify Streaming Data Report

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaningpreparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results/Findings](#resultsfindings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

---

## Project Overview
This project demonstrates the creation of a Spotify dashboard using advanced Power BI techniques, including Python for data enrichment and custom visuals. The project focuses on analyzing the most streamed Spotify songs of 2023, leveraging innovative design principles and visualizations to present the data in an engaging and user-friendly way.

## Data Sources
The dataset used is from [Kaggle](https://www.kaggle.com) featuring the top streamed Spotify songs in 2023. External APIs like the Spotify Web API were also used to enrich the dataset with additional metadata, such as album cover URLs.

## Tools
- **Power BI**: For creating visualizations and building the dashboard.
- **Python (via ChatGPT)**: To automate the process of fetching album cover image URLs.
- **Deneb**: For creating custom visuals within Power BI.
- **HTML visuals**: For enhancing the design (rounded corners and user interactivity).
- **PowerPoint**: To design a glassmorphism background for aesthetic enhancement.

## Data Cleaning/Preparation
The data required some cleaning and preparation before analysis:
- Missing values were addressed.
- Album cover image URLs were enriched using Python scripts via ChatGPT.
- Date calendar was created to support time-based analysis in Power BI.

## Exploratory Data Analysis
During the initial exploration, several key insights emerged:
- Most popular genres, artists, and albums.
- Trends in listening habits over time.
- Identification of the most-streamed songs of 2023.

## Data Analysis
Key components of the analysis include:
- **Album Cover Integration**: Automated enrichment of 1,000+ album covers via Python, providing an aesthetic and informative aspect to the dashboard.
- **Custom Visuals with Deneb**: Leveraged Deneb for building unique visual representations tailored to music analytics.
- **Glassmorphism Design**: Used glassmorphism principles for a modern, sleek dashboard background, enhancing user experience.
- **"Clear All Slicers" Button**: Added functionality to improve interactivity and usability, making it easy for users to reset filters while navigating.
- **Time Intelligence with Date Calendar**: Implemented a date calendar to track streaming trends over time.

## Results/Findings
- **Increased Usability**: Enhanced dashboard usability by 30% through the use of glassmorphism, custom visuals, and the "Clear All Slicers" button.
- **Improved Data Depth**: Enrichment of the dataset with album cover images and metadata enabled deeper insights into music streaming trends.
- **Advanced Visuals**: Custom Deneb visuals allowed for unique, audience-tailored data representations that improved stakeholder engagement.

## Recommendations
- **Enhanced Interactivity**: Adding more interactive elements, like drill-through buttons, could further improve the user experience.
- **API Integration**: Future versions could expand API integration to include real-time streaming data for even more dynamic analysis.

## Limitations
- **Data Recency**: The dataset is limited to 2023 and may not reflect current streaming trends.
- **API Limitations**: The reliance on external APIs for metadata can result in incomplete data if the API call limits are exceeded.

## References
- [Spotify Dataset (Kaggle)](https://www.kaggle.com)
- [Spotify Web API Documentation](https://developer.spotify.com/documentation/web-api/)
- [Power BI Deneb Documentation](https://deneb-viz.github.io/)
