# Semi-Supervised Generative Adversarial Network for Sentiment Analysis of drug reviews.

## Abstract

Sentiment analysis has become a very popular research topic and covers a wide range of domains such as economy, politics and health. In the pharmaceutical field, automated analysis of online user reviews provides information on the effectiveness and potential side effects of drugs, which could be used to improve pharmacovigilance systems. Deep learning approaches have revolutionized the field of Natural Language Processing (NLP), achieving state-of-the-art results in many tasks, such as sentiment analysis.
These methods require large annotated datasets to train their models. However, in most real-world scenarios, obtaining high-quality labeled datasets is an expensive and time-consuming task. In contrast, unlabeled texts task can be, generally, easily obtained. 
In this work, we propose a semi-supervised approach based on a Semi-Supervised Generative Adversarial Network (SSGAN) to address the lack of labeled data for the sentiment analysis of drug reviews,  and improve the results provided by supervised approaches in this task.
To evaluate the real contribution of this approach, we present a benchmark comparison between our semi-supervised approach and a supervised approach, which uses a similar architecture but without the generative adversal setting. 
Experimental results show better performance of the semi-supervised approach when annotated reviews are less than ten percent of the training set, obtaining a significant improvement for the classification of neutral reviews, the class with least examples. To the best of our knowledge, this is the first study that applies a SSGAN to the sentiment classification of drug reviews.  Our semi-supervised approach provides promising results for dealing with the shortage of annotated dataset, but there is still much room to improvement.

## BERT-Mini model

I. Turc, M.-W. Chang, K. Lee, and K. Toutanova, Well-read studentslearn better: The impact of student initialization on knowledge distillation, ArXiv, vol. abs/1908.08962, 2019.
## Dataset 

F. Gräßer, S. Kallumadi, H. Malberg, S. Zaunseder, Aspect-based sentiment analysis of drug reviews applying cross-domain and cross-data learning, in: Proceedings of the 2018 International Conference on Digital Health, ACM, 2018, pp. 121–125.