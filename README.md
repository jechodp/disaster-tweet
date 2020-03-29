# disaster-tweet
Twitter has become an important communication channel in times of emergency. The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies). But, it’s not always clear whether a person’s words are actually announcing a disaster.

# objectives
The objectives will try the Models to predicts which Tweets determine or contain words or information about real disasters and which one’s aren’t.

# dataset
Source: https://www.kaggle.com/c/nlp-getting-started/data

Columns :
1. id - a unique identifier for each tweet
2. text - the text of the tweet
3. location - the location the tweet was sent from (may be blank)
4. keyword - a particular keyword from the tweet (may be blank)
5. target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)

Files:
1. train.csv - the training set
2. test.csv - the test set
3. sample_submission.csv - a sample submission file in the correct format

# Sequence Process
1. Splitting Training and Test set into a 80:20 split
2. Tokenizing Input Dataset
3. Sequencing each tweet sentence according to the token defined in (1)
4. Padding each sequence if necessary to achieve an equal length sentence embedding
