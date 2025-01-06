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
