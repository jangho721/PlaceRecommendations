## Recommendation Systems
*Recommender systems* are systems that provide personalized recommendations for information, items, or content based on user preferences or behavior. These systems are widely used in various fields, such as online shopping, movie and music streaming, social media, news, location recommendations, images, web pages, and books, playing a crucial role in enhancing user experience.

## Project Description and Research Questions
The purpose of our project is to utilize **geographical location information** (such as the user's current location or specific places) to provide a satisfying user experience. To achieve this, we are developing a **location-based place recommendation system**, structured as follows in a [multi-stage](https://research.google/pubs/deep-neural-networks-for-youtube-recommendations/) process:

#### Stage 1: Generating Candidate Places
* Generate a list of candidate places for recommendation based on the location data.

#### Stage 2: Providing Recommendations
* For **new users**, recommendations are provided using *descriptive statistics*, *demographic-based recommendations*, and the *Multi-armed Bandit* algorithm.
* For **existing users**, algorithms such as *Content-based Filtering* and *Collaborative Filtering* are applied to deliver personalized recommendations.
<br>

This system aims to reduce decision-making time for users planning trips, scheduling meetings, or deciding on their next destination unexpectedly, ultimately providing a better overall experience.

### Future Work
* Path Generation Functionality: We plan to develop a feature that proposes optimal travel paths based on user preferences and location.

### Research Questions
1. Where do users visit, and how satisfied are they with these places?
2. What activities do users primarily engage in?
3. What is the extent of users' action radius?

## Datasets
The dataset used for this project is the [2023 Korea Jeju Travel Log data](https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=&topMenu=&aihubDataSe=data&dataSetSn=71780) provided by AIHub. It contains travel logs of 3,200 travelers, organized into 14 tables with a total of 217 columns. Data cleaning and feature engineering were performed to retain only non-empty values and select columns relevant to the project.

The recommendation system will be built around three categories: *accommodations*, *tourist attractions*, and *restaurants*. Therefore, the entire dataset was divided accordingly, and this project primarily focuses on **accommodation recommendations** as a first step.

Future work includes extending the system to recommend tourist attractions and restaurants, as well as applying the methodology to datasets such as [Seoul Travel Log data](https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=&topMenu=&aihubDataSe=data&dataSetSn=71776), the [Yelp Dataset](https://www.yelp.com/dataset), and data collected through web scraping.

## Data Cleaning
