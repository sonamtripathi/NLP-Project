# NLP-Project

# Topic Modeling Articles using Non-Matrix Factorization

#Problem Statements: -

For a financial company, customer complaints carry a lot of importance, as they are often an indicator of the shortcomings in their products and services. 
If these complaints are resolved efficiently in time, they can bring down customer dissatisfaction to a minimum and retain them with stronger loyalty. 
This also gives them an idea of how to continuously improve their services to attract more customers.

These customer complaints are unstructured text data; so, traditionally, companies need to allocate the task of evaluating and assigning each ticket to the relevant department to multiple support employees. 
This becomes tedious as the company grows and has a large customer base.

We need to build a model that is able to classify customer complaints based on the products/services. 
By doing so, you can segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue.

# Topic Modeling using Non-Negative Matrix Factorization
Here we will be using NMF(Non-Negative Matrix Factorization) with the help of this technique, which is an approach under topic modelling, we will detect patterns and recurring words present in each ticket. 
This can be then used to understand the important features for each cluster of categories.
By segregating the clusters, we will be able to identify the topics of the customer complaints.

What is NMF(Non-Negative Matrix Factorization) ?
Non-Negative Matrix Factorization is a statistical method that helps us to reduce the dimension of the input corpora or corpora. Internally, it uses the factor analysis method to give comparatively less weightage to the words that are having less coherence. 
Non-Negative Matrix Factorization (NMF) is an unsupervised technique so there are no labeling of topics that the model will be trained on. 
The way it works is that, NMF decomposes (or factorizes) high-dimensional vectors into a lower-dimensional representation. 
These lower-dimensional vectors are non-negative which also means their coefficients are non-negative.
