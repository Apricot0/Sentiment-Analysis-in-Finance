# Sentiment-Analysis-in-Finance
GPT-3 and GPT-Neo zero-shot solution for financial sentiment analysis
## Abstract
This project explores various approaches to sentiment classification of financial field-related sentences. We experimented with different models and strategies, including fine-tuning on small-sized pre-trained models, zero-shot and few-shot learning on Large Language Models (LLMs). Our objective was to identify the most effective method for sentiment classification of financial text data. We evaluated our models on a dataset of financial news articles and reports, and compared their performance using metrics such as precision, recall, and F1 score. Our findings suggest that the model that provides the best results for sentiment classification in the financial domain out of all of our solution approaches is the GPT-3.5 Turbo model when given 6 correctly classified samples. Overall, this project provides valuable insights for practitioners and researchers working on sentiment analysis in finance.
## Introduction
The financial industry generates vast amounts of text data every day, including news articles, company reports, social media posts, and more. Analyzing this data to determine the sentiment behind it can provide valuable insights for investors, analysts, and other stakeholders. However, sentiment analysis of financial text presents unique challenges, including the complexity of financial language and the need for accurate classification of nuanced sentiments. In addition, texts related to finance are often mixed with a large number of numbers rather than just words. 1
These numbers largely constitute the core meaning of the text, and it is difficult to accurately
infer sentiment through this digital information.
The overall goal of our project is to find a better way to perform sentiment analysis on
financial-related sentences. Specifically, we aim to develop a model that can accurately classify a
sentence as either positive, negative, or neutral. We have experimented with various machine
learning techniques, including fine-tuning on pre-trained models, zero-shot learning, and
few-shot learning on Large Language Models (LLMs).
In order to identify the most effective approach, we evaluate the performance of each model
using standard metrics such as precision, recall, and F1-score. Our ultimate objective is to
identify the best-performing model that can accurately classify financial sentences into their
corresponding sentiment classes based on these metrics.
In this paper, we will present our methodology, data collection, and experimental results. Our
contributions include a thorough evaluation of different sentiment analysis techniques on a
dataset of financial news articles and reports. Our findings will provide insights for practitioners
and researchers working in the field of sentiment analysis in finance, and help to advance our
understanding of this challenging and important problem.
In our experiments, we find that few-shot prompting on LLMs is much more effective than
zero-shot prompting. Few-shot prompting on Flan-T5-XXL, a model with 11 billion parameters,
outperformed GPT-3 Davinci, a model with 175 billion parameters, using zero-shot prompting
(Weighted F1 = 0.469728 vs 0.431026).

Check the PDF for detail
