# Memotion
NLP
Abstract
Information on social media comprises various modalities such as textual, visual and audio. NLP and Computer Vision communities often leverage only one prominent modality in isolation to study social media. However, the computational processing of Internet memes needs a hybrid approach. The growing ubiquity of Internet memes on social media platforms such as Facebook, Instagram, and Twitter further suggests that we can not ignore such multimodal content anymore. To the best of our knowledge, there is not much attention towards meme emotion analysis. The objective of this proposal is to bring the attention of the research community towards the automatic processing of Internet memes. The task Memotion analysis will release 8K annotated memes - with human-annotated tags namely sentiment, and type of humour that is, sarcastic, humorous, or offensive.

Since the previous decade,Memes have grown to be one of the hottest subjects on the internet and arguably, the most common kind of comedy seen on social media platforms nowadays.But despite their huge growth ,there is not much attention towards meme emotion analysis. Because of this growth and the kind of effect social media has on pop culture, analysing memes might come in handy and even become a necessity in the near future.
Memes are usually images with text written inside, so the kind of sense and humour they carry is a result of these two parts together.Therefore , to classify their kind of sentiment and humour , it is necessary to consider both parts;which is our approach in solving this problem.
The objective of this proposal is to bring the attention of the research community towards the automatic processing of Internet memes.

The Memotion Analysis Task :
Task A- Sentiment Classification: Given an Internet meme, the first task is to classify it as a positive, negative or neutral meme.
Task B- Humour Classification: Given an Internet meme, the system has to identify the type of humour expressed. The categories are sarcastic, humorous, and offensive memes. If a meme does not fall under any of these categories, then it is marked as another meme. A meme can have more than one category.
Task C- Scales of Semantic Classes: The third task is to quantify the extent to which a particular effect is being expressed. Details of such quantifications are reported in Table 1. Appropriate annotated data will be provided.
Approaches
Memes are essentially bimodal. They have both Text and Image components. We used both bimodal (text and image) and unimodal (text-only) approaches as listed below:
Bimodal
ffnn_cnn_svm: Feed Forward Neural Network with Word2vec for text, CNN for images, combined via an SVM classifier
mmbt: Multimodal Bitransformer
Unimodal
naive_bayes: Simple Naive Bayes classifier
ffnn_w2v: Feed Forward Neural Network with Word2vec
bert: Bidirectional Encoder Representations via Transformers

Evaluation Criteria
For Task A: macro F1
For Task B and C: macro F1 for each of the subtasks, and then average.
Results
To classify the given meme into their kind of  sentiment and humour 
Task A - Sentiment Classification
Task B- Humour Classification
Task C- Scales of Semantic Classes

Link : Memotion Dataset 7k | Kaggle

Additional :
Kaggle Notebook :
https://www.kaggle.com/code/manichandanathumati/memotion-analysis-a-c
