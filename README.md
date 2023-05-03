# Tf-idf-and-count-vectors-NLP-

# Introduction:

![alt text](https://contenthub-static.grammarly.com/blog/wp-content/uploads/2018/05/how-to-write-an-introduction-760x400.jpg)

Vectorization in NLP (Natural Language Processing) refers to the process of representing textual data in the form of numeric vectors that can be used as input for machine learning models. In other words, it is the conversion of textual data into a numerical format that can be processed by algorithms.

Vectorization is an important step in NLP because machine learning models typically require numerical input data. By converting text into a vector format, we can leverage a wide range of numerical techniques to analyze and process language data.

# What has been performed

![alt text](https://th.bing.com/th/id/R.004b727c2eb076edeb9ca62e49f48a8b?rik=jrD9KZ9J3tfbaw&riu=http%3a%2f%2fdavidodefense.com%2fwp-content%2fuploads%2fwhat.jpg&ehk=3cwHsqO3ccyMJ5i94xuVfwa5PJ3bzG7ap2cTHgJoOLw%3d&risl=&pid=ImgRaw&r=0)

In this dataset I have performed two types to vectors:

1.Count vectors

2.Tf-Idf vectore.

I have performed both these vectorization to demonstrate the difference between the two. However for more clarity I have give a theoritical explanation below.

# Types of vectors

1.Count vectors represent each document as a vector of word counts. In other words, the frequency of each word in the document is counted and used as a feature in the vector representation. This means that the resulting vector will have a high value for words that occur frequently in the document and a low value for words that occur rarely or not at all.

2.On the other hand, TF-IDF vectors represent each document as a vector of weighted word counts. In addition to counting the frequency of each word in the document, the TF-IDF method takes into account how often each word appears in the entire corpus of documents. Words that appear frequently across all documents will have a lower weight, while words that appear rarely in the corpus will have a higher weight.

# Conclusion

![alt text](https://th.bing.com/th/id/OIP.iJTHcqqnP7d8ntbe_QL1RQHaFj?pid=ImgDet&rs=1)

In summary, count vectors represent documents as a vector of word counts, while TF-IDF vectors represent documents as a vector of weighted word counts that take into account the importance of each word in the entire corpus.

# Thank you