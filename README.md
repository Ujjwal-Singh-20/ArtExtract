## Task 1: Convolutional-Recurrent Architectures </br>
### Painting Classification and Outlier Detection</br>
This project focuses on classifying paintings by Artists, Genres, and Styles, using AI-based models. Additionally, it includes outlier detection to identify paintings that deviate significantly from their assigned attributes.

**Key Features**</br>
**Three Models:** Separate trained models for Artists, Genres, and Styles classification.

**Dataset Handling:** Processes .npz files dynamically, including partial batches.

**Outlier Detection:** Detects anomalies using techniques like centroid distances, k-means clustering, and Isolation Forest.




## Task 2: Similarity</br>
### Top-N Retrieval and Pairwise Similarity</br>
This project is designed to calculate pairwise similarity scores and perform Top-N similarity retrieval using pre-trained embeddings. It provides tools to store ground truth labels and predictions in a unified JSON file, enabling efficient updates and evaluation for similarity-based tasks.

**What It Does**</br>
**Pairwise Similarity:** Compute the cosine similarity score between two items (e.g., paintings) using their embedding vectors.

**Top-N Retrieval:** Find the top-N most similar items for a given query item based on similarity scores.

**Integrated Labels and Predictions:** Store similarity predictions alongside ground truth labels in a unified JSON file for easy access and evaluation.

**Model Evaluation:** Includes tools to calculate metrics like Precision, Recall, and F1-Score for assessing performance.

</br></br>

***many files like the preprocessed batches, models, etc. are not uploaded as the total size exceeds 60gb, which serves a problem during uploading***
