# Car-Make-Model-KNN-Clustering

**Unsupervised Car Image Clustering**
This project focuses on developing an unsupervised learning pipeline to identify and cluster similar car images based on their visual features. By utilizing a custom convolutional neural network (ResNetSimCLR), we extract meaningful embeddings from the images, enabling us to group them effectively.

**Project Highlights**
Image Embedding: Leveraging the power of ResNetSimCLR, we generate high-quality embeddings that capture the essential characteristics of car images.
Clustering and Visualization: Using t-SNE, we reduce the dimensionality of the embeddings, allowing for clear visualization and interpretation of the clusters formed by similar car makes and models.
Quality Evaluation: The performance of the clustering is assessed through the Silhouette Score, providing insights into the effectiveness of the grouping and guiding iterative optimizations.
Efficient Implementation: The entire model is built with PyTorch, utilizing GPU acceleration to enhance the efficiency of embedding extraction and model training.


**Skills and Technologies Used**
Python
PyTorch
ResNetSimCLR
t-SNE
Silhouette Score
Unsupervised Learning
Convolutional Neural Networks (CNN)
