# Detecting vulnerabilities in source code using ML

As software systems grow in complexity, identifying and mitigating security vulnerabilities at the source code level has become increasingly important. This research focuses on leveraging machine learning techniques for vulnerability detection in C/C++ programs, with an emphasis on comparing a diverse set of models and data representations. Previous work in this field has been also analyzed, in order to make some improvements.
I decided to evaluate classical machine learning models, including Random Forests, Decision Trees, Boosting, k-Nearest Neighbors and Logistic Regression, using multiple vectorization techniques such as Count Vectorizer, TF-IDF, and Hashing. These approaches are applied to Abstract Syntax Trees (ASTs) representations of source code, aiming to understand how well traditional models perform in code-based security classification tasks.
In addition to classical methods, I explored the structural aspects of code through deep learning. Abstract Syntax Trees (ASTs) are processed using convolutional and recurrent neural networks (CNN and LSTM) to capture syntactic patterns indicative of vulnerabilities. Furthermore, we investigate the use of Control Flow Graphs (CFGs) in combination with Graph Neural Networks (GNNs) to capture more complex, execution-based relationships within code.
To ensure a comprehensive evaluation, we incorporate various datasets that range in complexity—from artificially generated simple code snippets to real-world, complex software projects. This allows us to analyze model performance across different code granularities and abstraction levels. 
The goal is to highlight the strengths and trade-offs of different machine learning approaches in the context of source code vulnerability detection. Overall, this research suggests a hybrid approach, combining both traditional and deep learning techniques. In addition, the analysis of current datasets used for this problematic can help future work in this area.


# HOW TO USE

Just download the datasets and use Collab or simply run the notebooks locally, but add the datasets into the same folder with the notebooks.
