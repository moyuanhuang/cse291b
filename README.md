# cse291b Final Project

## Part 1. reproduce the experiment on Yelp Dataset(without publicly available code)
1. Try to reproduce result on Yelp Dataset to check the origin experiment's generalizability
  - number of users (per state) with location and gender
  - regional coverage of the data
  - 10 most gender specific words based on relativerf-idf
  - correlation of emoticon-use for gender
  - Distribution of the 10 most frequent categories per gender
2. Only focus on **gender** and **location** part, since no age information is provided in Yelp Dataset

## Part 2. Rating prediction with sociolinguistic findings
1. build a rating predictor with/without age/gender, since it is said to be strongly correlated to ratings
  - baseline model
  - + age/gender information
  - + reviews text with different words selected from part 1
