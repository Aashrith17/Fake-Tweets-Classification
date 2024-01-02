# Fake-Tweets-Classification
In this project, our primary objective was to discern between real and fake disaster-related tweets, employing a diverse set of machine learning algorithms. Python served as the programming language of choice, owing to its versatility in data processing and seamless integration of machine learning frameworks. Crucial libraries such as TensorFlow, scikit-learn, pandas, and numpy were instrumental in preprocessing categorical data.

To transform the textual content into a format suitable for model training, we utilized a text vectorizer. Initial efforts involved training conventional machine learning models, including logistic regression, decision trees, and random forest, yielding respective accuracies of 80%, 70%, and 78%.

Acknowledging the potential for further performance improvement, deep learning models were introduced. Bidirectional LSTMs, implemented using the Keras library, resulted in a notable accuracy increase to 83%. Recognizing the pivotal role of language models in text-centric tasks, we incorporated advanced techniques to refine accuracy.

The project featured the integration of the BERT (Bidirectional Encoder Representations from Transformers) model, leveraging the ktrain library for training. This state-of-the-art algorithm significantly elevated performance, culminating in an impressive accuracy of 94%. The synthesis of diverse machine learning and deep learning methodologies underscored a comprehensive approach to tweet classification, with the BERT model emerging as an especially potent solution for this text-based categorization challenge.
