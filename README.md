this project showcases the development of a text classification model using BERT, addressing the challenge of identifying generated content in essays. The journey involved data loading, exploration, preprocessing, model selection, training, and evaluation. While Distil BERT was considered, the time constraints led to the choice of the BERT model. The presented model demonstrates promising results and lays the foundation for future enhancements and explorations in the realm of natural language processing.

BERT (Bidirectional Encoder Representations from Transformers) is a type of artificial intelligence model that's really good at understanding language. It learns by looking at a lot of text data and figuring out the relationships between words. When it comes to detecting AI-generated text, BERT is trained to recognize patterns in language that might indicate if a piece of text was written by a human or generated by a machine. It does this by understanding the context and connections between words. For example, it can pick up on subtle cues that might be more common in machine-generated text. By using BERT, we can create a smart system that helps identify if a text was likely created by a computer.


The project leveraged several key libraries and tools:

Transformers: Utilized for accessing pre-trained BERT models and tokenizers.
NLTK (Natural Language Toolkit): Employed for text preprocessing tasks, including stopwords removal.
TensorFlow and TensorFlow Text: Used for constructing and training the neural network model.
Seaborn and Matplotlib: Employed for data visualization and exploration.
Pandas: Used for data manipulation and handling.

Results:-
Run
2004.5s - GPU P100
Public Score
0.80
 

