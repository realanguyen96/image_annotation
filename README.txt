Individual assignment using deep learning and machine learning to build text-based classification model:
 
1. Image annotation by Convolutional Neural Network (CNN) which is TensorFlow and keras from CIFAR-100 dataset

Result: accuracy around 39% only due to low resolution of trained images (32x32)

2. Summarization and visualization of word cloud from tweets about Covid-19. Text-to-embedding by Gensim library then classify by machine learning classifier (RandomForest) to predict sentiment of tweets based on text

Result: 5 levels of Sentiment from Extremely Negative to Extremely Positive. Around 45-50% of accuracy except Neutral incentive (74%). Can be improved easily by either reduced from 5 to 3 levels (negative - neutral - positive) or increase trained data size