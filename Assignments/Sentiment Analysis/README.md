# IMDB sentiment analysis Implemented in Julia

## Training model 
### The training model is based Naive Bayes model are used as the training model, with N-gram extension. That resulted in a maximum accuracy of **0.84588** with a trigram model
## Data preprocicing:
- Irrelvent charactes and punctuation mark were removed
- Stopwords were removed from the data
- Words were mapped to unique indicies for easier proccess. 
- Total of 25,000 reviews were used for traingin (12,500 positive and 12,500 negative) and another 25,000 were used for testing.

The data were downloaded from Stanford AI lab at this [https://ai.stanford.edu/~amaas/data/sentiment](link)

## Benckmark results for different N-grams models
` ` `
modeling data in 1 gram model
Naive Bayes model with 1 gram model prodcued accuracy of **0.8342**
modeling data in 2 gram model
Naive Bayes model with 2 gram model prodcued accuracy of **0.84492**
modeling data in 3 gram model
Naive Bayes model with 3 gram model prodcued accuracy of **0.84588**
modeling data in 4 gram model
Naive Bayes model with 4 gram model prodcued accuracy of **0.84584**
modeling data in 5 gram model
Naive Bayes model with 5 gram model prodcued accuracy of **0.8458**
modeling data in 6 gram model
Naive Bayes model with 6 gram model prodcued accuracy of **0.8458**

` ` `

