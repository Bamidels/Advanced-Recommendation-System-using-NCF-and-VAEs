# Advanced-Recommendation-System-using-NCF-and-VAEs
Building an Advanced Recommendation System using Neural Collaborative Filtering (NCF) and Variational Autoencoders (VAEs)

Introduction

Recommendation systems are machine learning applications that predict user preferences and provide personalized recommendations for various types of items, such as movies, books, and products. This project aims to build an advanced recommendation system that leverages traditional collaborative filtering and matrix factorization techniques, as well as cutting-edge deep learning techniques such as neural collaborative filtering (NCF) and variational autoencoders (VAEs), to improve recommendation accuracy.

Model under investigation

We investigate the combination of traditional collaborative filtering and matrix factorization techniques with advanced deep learning-based techniques such as NCF and VAEs to build our recommendation system. NCF combines neural networks with matrix factorization to make recommendations and outperforms traditional matrix factorization methods. VAEs model user and item embeddings in a joint latent space, improving recommendation accuracy by capturing complex user-item interactions.

Methodologies

We use a large-scale ratings dataset that contains user ID, movie ID, rating, and timestamp attributes to train and test our recommendation system. We build a rank-based recommendation system as a baseline model, followed by implementing traditional collaborative filtering and matrix factorization techniques. We integrate NCF and VAEs into our recommendation system to improve its accuracy and performance.

We evaluate each model's performance using multiple evaluation metrics, including precision, recall, and F1-score, using evaluation criteria such as False Negative (FN) and False Positive (FP) to minimize the loss of opportunity for service providers and resources.

Completion of project

We complete the project by building and comparing each recommendation system's performance using various evaluation metrics. The final decision on the best model is based on factors such as recommendation quality, evaluation metrics, and time efficiency.

Timeline

Week 1: Dataset exploration and preparation, data preprocessing, and cleaning
Week 2: Building the rank-based recommendation system and traditional collaborative filtering and matrix factorization techniques
Week 3: Integrating NCF and VAEs into the recommendation system
Week 4: Evaluating and comparing the performance of each model, writing the final report

Dataset

The dataset used for this project contains 100,836 ratings and 3,683 tag applications across 9,742 movies. These data were created by 610 users between March 29, 1996, and September 24, 2018. This dataset was generated on September 26, 2018.

Additional Information:

In this case study, we built recommendation systems using four different algorithms:

• Rank-based using averages
• User-User similarity-based collaborative filtering
• Item-Item


References

He, X., Liao, L., Zhang, H., Nie, L., Hu, X., & Chua, T. S. (2017). Neural collaborative filtering. In Proceedings of the 26th International Conference on World Wide Web (pp. 173-182).
Koren, Y., Bell, R., & Volinsky, C. (2009). Matrix factorization techniques for recommender systems. Computer, 42(8), 30-37.
Liang, D., Altosaar, J., & Charlin, L. (2018). Factorization meets the neighborhood: a multifaceted collaborative filtering model. In Proceedings of the 24th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining (pp. 1048-1057).
Li, H., Kadav, A., Samet, H., & Goyal, P. (2020). SAsRec: Self-Attentive Sequential Recommendation. In Proceedings of the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval (pp. 1545-1548).


