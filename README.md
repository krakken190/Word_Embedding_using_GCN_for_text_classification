# Word_Embedding_using_GCN_for_text_classification

🔷In this project, we aimed to leverage the power of Word Embeddings with Graph Convolutional Networks (GCNs) to process text data and perform classification tasks. Here's a summary of what we achieved:

➖Word Embeddings: We utilized pre-trained models like Word2Vec or GloVe to convert our input text data into dense word embeddings. These embeddings capture semantic information and enable us to represent each word as a vector.

➖Graph Construction: We constructed a graph structure using the word embeddings. Each word in the text became a node in the graph, and the connections between nodes captured semantic relationships. Techniques like co-occurrence, dependency parsing, or semantic similarity were used to define the edges between nodes.

➖GCN Architecture: We implemented the Graph Convolutional Networks (GCNs), which consisted of graph convolutional layers, activation functions, and pooling operations. These layers learned representations that incorporated both local and global information from the graph structure.

➖Training and Evaluation: We trained the GCN model using a training set, optimizing the model's parameters with gradient-based optimization algorithms like Adam or SGD. We evaluated the model's performance on a validation or test set using metrics such as accuracy, precision, recall, or F1-score.

➖Classification: Finally, we used the learned representations from the GCN's output layer for classification tasks. We applied the trained model to classify new text data, predicting whether it belongs to a specific class (e.g., spam or not spam).

➖By combining Word Embeddings with GCNs, we were able to capture the contextual information of words and their relationships, leading to improved performance in text classification tasks.
