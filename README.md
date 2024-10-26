# Shark Attacks Analysis
The dataset is provided by [Mysar Ahmad Bhat](https://www.kaggle.com/datasets/mysarahmadbhat/shark-attacks).

## Data Cleaning
* Unspecified month were removed.
* Year < 1900 were removed.
* Empty types and invalid types were labelled as "unknown" instead.
* Territory of Cocos area were removed.
* Empty area were removed.
* Empty location were labelled as "unknown".
* Unspecified activity were labelled as "unknown".
* Empty activity were labelled as "unknown". May further consider approaches for text manipulations if interested.
* Empty and "N" sex were labelled as "unknown".
* Incomplete age information were either labelled as "unknown" or a number if information was provided.
* Empty fatal were labelled as "unknown".
* Empty time were labelled as "unknown". Further categorisation from hours or hours from categories may be performed.
* Empty species were labelled as "unknown".
