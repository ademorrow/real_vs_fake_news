Transformers for natural language processing (NLP) have become a standard for high
model accuracy metrics on various NLP tasks. Classification is a natural fit for transformer
models, and the Hugging Face library has evolved as a popular resource for readily available
large scale pre-trained models with great performance on downstream tasks. This project used
the Hugging Face “bert-base-uncased” model to classify news articles into “real” and “fake”
news. The results show that fine-tuned pretrained models can achieve extremely high accuracy;
however, attempting inference with these fine-tuned models on data pulled from different
sources, topics, and news cycles yielded poor performance.  
