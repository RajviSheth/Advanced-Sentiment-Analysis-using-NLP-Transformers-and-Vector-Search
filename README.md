# Advanced-Sentiment-Analysis-using-NLP-Transformers-and-Vector-Search
Advanced Sentiment Analysis using NLP Transformers and Vector Search

This project first Generates Sentiment labels and scores based on the customer reviews. Then it stores them in a Pinecone index as metadata (alongside respective text vectors). Then it queries the Pinecone index on selected areas to understand customer opinions.

This graph is produced by searching in the vector embeddings and analyzing hotels in London based on how they are reviewed based on features like Room Size, Cleanliness, Staff, Food and AC.
![graph](https://github.com/RajviSheth/Advanced-Sentiment-Analysis-using-NLP-Transformers-and-Vector-Search/assets/13827244/148a21e6-ad41-43ac-bfd4-4be6e91f6a7d)



The Dataset used from huggingFace : https://huggingface.co/datasets/ashraq/hotel-reviews.
The Model used for this project: https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment
