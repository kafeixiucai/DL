# DL

Chapter 5 Machine Learning Basics
Machine learning textbook: Murphy (2012)[Machine Learning: a Probabilistic Perspective] or Bishop(2006)[Pattern Recognition and Machine Learning]


Chapter 5.1 Learning Algorithms 
Learning: Mitchell (1997) provides the definition “A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P, if its performance at tasks in T, as measured by P, improves with experience E.” 
5.1.1 The Task
Definition: how the machine learning system should process an example( an example is a collection of features that have been quantitatively measured).
Examples: Classification; Classification with missing inputs; Regression; Transcription; Machine translation; Structured output; Anomaly detection; Synthesis and sampling; Imputation of missing values; Denoising; Density estimation or probability mass function estimation; and etc. 

5.1.2 The Performance Measure 
Definition: A quantitative measure that evaluate the performance of a machine learning algorithm.
Mention: It’s difficult to decide what should be measured, and these kind of design choices depend on the application.

5.1.3 The Experience
Definition: The content that the machine learns from the data?
A dataset: a collection of examples, usually denoted by a matrix(row for example, column for feature), or a set(for examples of different number of features).
Unsupervised learning algorithm: density estimation; synthesis; denoising; clustering; and etc. Supervised learning: with label or target. The lines between them are often blurred.


Questions:
[1]: P104, for density estimation, how to define the performance measure? 
[2]: P104, how to understand the Experience? (P107, it’s mentioned that there is no rigid taxonomy of experiences.)
[3]: P106, what is semi-supervised learning? Mulit-instance learning? Reinforcement learning? 

(2017/9/17) 
