# Quickstart:

Launch with    <a href="https://colab.research.google.com/github/JonasHendl/TopicModelingDemo/blob/main/tutorial.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>
---
Or clone it if you have a working python IDE.


This repository gives you a quick intuition of how you can extract informaiton from customer reviews. You will use the package BERTopic which provides a lot of functionality. 


# Challenge:

You just started your position as data scientist at Singapore Airlines. Management gives you a list of reviews and wants to know:

+ What do our customers appreciate most?
+ What is the biggest pain-point or weakness?
+ Is there something else you notice?

## The Data:
Singapore Airlines Reviews
taken from: https://www.kaggle.com/datasets/kanchana1990/singapore-airlines-reviews

I calculated sentence embeddings ahead of time with [this Sentence Transformer](https://huggingface.co/T-Systems-onsite/cross-en-de-roberta-sentence-transformer).


Description directly copied from Kaggle:

### Overview:
The "Singapore Airlines Reviews" dataset aggregates 10,000 anonymized customer reviews, providing a broad perspective on the passenger experience with Singapore Airlines. This extensive collection is instrumental for data-driven insights into customer satisfaction and service quality.

### Data Science Applications:
Ideal for sentiment analysis, trend spotting, and predictive analytics, this dataset is a valuable asset for improving customer experience and operational efficiency.

### Column Descriptors:

published_date: Date and time of review publication.\
published_platform: Platform where the review was posted.\
rating: Customer satisfaction rating, from 1 (lowest) to 5 (highest).\
type: Specifies the content as a review.\
text: Detailed customer feedback.\
title: Summary of the review.\
helpful_votes: Number of users finding the review helpful.


### Ethical Considerations:
Compiled with a commitment to privacy, all personal identifiers have been removed to ensure ethical standards.

### Acknowledgements:
Thanks to TripAdvisor for the review platform and Singapore Airlines for the service quality reflected in the dataset. The thumbnail features the Singapore Airlines logo, acknowledging the brand's influence on the data."
