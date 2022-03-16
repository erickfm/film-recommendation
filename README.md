# Movie Recommendations

Public copy of Movie Recommendations project work done by GitHub users: erickfm, codebeard1, and chima1218

## Overview

Can we suggest good recommendations for a given film/user?
Video streaming services such as Netflix, Disney+, Hulu, and Amazon having been gaining momentum over the years but the pandemic has brought on heightened demand for video streaming services. According to Grand View Research the market size of video streaming services in 2020 was 50B which is anticipated to grow at a compounding rate of 21 percent year over year. So having well curated content and recommendations will continue to be table stakes for video streaming services.

As a MIDS research team we are interested in finding new ways to make and validate movie recommendations for users. So of the various algorithms what can we learn about movie characteristics that would make for good recommendations, and how do these recommendations compare to how users are curating/rating their own movie lists.  

Our recommendation engine will learn various similarities among movie features to make top ten recommendation of films related to a given film/user. We will then validate these recommendation results based upon user defined lists/rates to determine if our recommendations are "good" recommendations.

## GitHub Repository structure
- /data: This folder contains the movie data for our recommendation systems

- final_keras_recommender.ipynb: this is the notebook code for the Keras model with collaborative filtering (user similarity)
- movie-recommendations-lightfm.ipynb: this is the notebook code for the LightFM model
- movie-recommendations-content-based-filtering.ipynb: this is the notebook code for the Content-based Filtering model
- movie-recommendations-hybrid-filtering.ipynb: this is the notebook code for the Hybrid Filtering model

- data_prep.ipynb: this is an older notebook that was used to process an older data source
- movie-recommendations.ipynb: this is the old notebook code for the Naive Bayes model
