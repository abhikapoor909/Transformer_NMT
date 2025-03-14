After learning from Krish Naik’s and CampusX’s YouTube videos, along with studying the groundbreaking paper “Attention Is All You Need,” I attempted to implement the Transformer architecture in PyTorch. To validate my implementation, I experimented with the Neural Machine Translation (NMT) problem, specifically focusing on English-to-French translation.

However, training the model proved to be quite challenging due to the large dataset size and high-dimensional feature space. To make it feasible on Kaggle, I had to significantly reduce input dimensions and lower the batch size to avoid memory issues. Despite these optimizations, limited computational resources made it difficult to experiment with larger architectures, fine-tune hyperparameters, or train the model for extended periods.

As a result, the performance achieved so far is not very promising, with translation quality still falling short of expectations. However, moving forward, I plan to refine my approach and explore better training strategies to improve results. Some potential optimizations include:
	•	Leveraging pretrained models like mBART, T5, or MarianMT to reduce training time.
	•	Using mixed precision training with PyTorch AMP (Automatic Mixed Precision) to lower memory usage.
	•	Implementing gradient accumulation to simulate larger batch sizes without exceeding memory limits.
	•	Experimenting with model quantization and pruning to make inference faster and reduce computational overhead.

 While the current results are not as good as expected, I am confident that by optimizing the training process and exploring more efficient architectures, the performance of my Transformer-based model will improve significantly over time.
