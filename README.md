## NLP-in-Tensorflow
Building natural language processing systems using TensorFlow starting from processing text to generating poetry with neural networks (LSTMs)

## Skills 
Natural Language Processing & Generating, Tokenizing, Generating n_grams, Padding, Embeddings, Bidirectional LSTM, Hyper-Parameters, Tensorflow, Keras, Python

These notebooks are submitted as part of assignments while completing a course in Coursera
* [DeepLeaning.ai](https://www.coursera.org/learn/natural-language-processing-tensorflow)

## Included notebooks are 
1) [Tokenization_Padding_in_Tensorflow.ipynb](https://github.com/TechWithRamaa/NLP-in-Tensorflow/blob/main/Tokenization_Padding_in_Tensorflow.ipynb)
   * Embarked on a journey into the world of Natural Language Processing (NLP) by learning how to tokenize words, transforming them into numbers that a machine can understand
   * This foundational knowledge paved the way for understanding how machines can begin to comprehend human language
   * Dataset - [kaggle/bbc](https://www.kaggle.com/c/learn-ai-bbc/data)

2) [BBC_News_Articles_Neural_Network_Classifier.ipynb](https://github.com/TechWithRamaa/NLP-in-Tensorflow/blob/main/BBC_News_Articles_Neural_Network_Classifier.ipynb)
   * Explored Embeddings
   * These powerful tools map our vocabulary into higher-dimensional space, allowing the machine to grasp the subtleties of word meanings
   * Learned how words with similar sentiments are clustered together, and how the direction of these vectors can reveal the underlying emotions in text
   * The introduction of subword tokenization further highlighted the importance of not just the words themselves, but also the sequence in which they appear
   * Dataset - [kaggle/bbc](https://www.kaggle.com/c/learn-ai-bbc/data) classifying articles into 5 categories ['tech', 'business', 'sport', 'sport', 'entertainment']

3) [Text_Classification_Keras_LSTMs.ipynb](https://github.com/TechWithRamaa/NLP-in-Tensorflow/blob/main/Text_Classification_Keras_LSTMs.ipynb)
    * Explored various model formats that help capture context (forward & backward), allowing for a more nuanced understanding of sentiment in text
    * Learnt best practices for defining Hyper parameters
    * Adjusting hyper parameters & analyzing accuracy of neural network models with different Keras Layers like Conv1D, Dropout, GlobalMaxPooling1D, MaxPooling1D, LSTM and Bidirectional(LSTM)
    * Started experimenting with text prediction, laying the groundwork for creating entirely new sequences of words resulting in Poetry
    * Dataset - [kaggle/bbc](https://www.kaggle.com/c/learn-ai-bbc/data) classifying articles into 5 categories ['tech', 'business', 'sport', 'sport', 'entertainment']

4) [Creating_Poetry_With_Bidirectional_LSTMs.ipynb](https://github.com/TechWithRamaa/NLP-in-Tensorflow/blob/main/Creating_Poetry_With_Bidirectional_LSTMs.ipynb)
    * Developed a creative tool by building a poetry generator
    * Drawing inspiration from traditional Irish songs and Shakespearean poetry, trained our model to generate beautiful verses
    * Tokenizing, Generating n_grams, Padding, defined model with Embedding layer & Bidirectional LSTM, Generated verses with 100 words by inputting seed texts
    * Dataset - [shakespeare.org](https://www.opensourceshakespeare.org/views/sonnets/sonnet_view.php?range=viewrange&sonnetrange1=1&sonnetrange2=154)
   
