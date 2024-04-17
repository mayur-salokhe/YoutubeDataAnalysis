# YouTube Data Analysis Project

## Introduction

The exponential rise in online video consumption has positioned platforms like YouTube at the forefront of digital media. With billions of users and an extensive library of content, YouTube offers a fertile ground for understanding user behavior, content preferences, and online community dynamics. This project embarks on an exploratory journey through YouTube's vast data ecosystem to uncover the factors influencing video performance and audience engagement.

## Aims and Objectives

### Aims:

- Explore the YouTube API and obtain video data.
- Analyze video data to verify common assumptions about video performance on YouTube.
- Utilize NLP techniques to explore trending topics and user interactions within video content.

### Objectives:

1. Investigate the impact of likes, comments, video duration, and title length on video views.
2. Determine the correlation between the number of tags and video performance.
3. Analyze the upload frequency of creators and identify popular upload days.
4. Utilize NLP techniques to identify popular topics and questions from video titles and comments.

## Steps of the Project

1. **Data Acquisition:** Obtain video metadata via the YouTube API, focusing on the top channel (T-Series).
2. **Data Preprocessing:** Clean and preprocess the acquired data, and engineer additional features for analysis.
3. **Exploratory Data Analysis:** Perform in-depth analysis to uncover insights into video performance and audience engagement.
4. **Conclusions:** Summarize findings and insights derived from the analysis.
5. **Ethical Considerations:** Discuss the ethical implications of utilizing data from the YouTube API.

## Ethics of Data Source

The usage of the YouTube API is subject to quota limits to ensure fair usage and maintain service quality for all developers. The default quota allocation is 10,000 units per day, with the option to request additional quota if needed. As all data obtained from the API is public and accessible to anyone on the internet, privacy concerns are minimal. The data is used strictly for research purposes and not for commercial gain.

## Getting Started

To replicate the analysis conducted in this project, follow these steps:

1. Obtain a developer key for the YouTube API.
2. Use the key to request video data via the YouTube API.
3. Preprocess the acquired data and engineer additional features as necessary.
4. Perform exploratory data analysis using appropriate tools and techniques.
5. Document and interpret the findings, drawing conclusions based on the analysis.

## Dependencies

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Natural Language Toolkit (NLTK)
- WordCloud

