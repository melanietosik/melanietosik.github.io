---
title: Text mining in Java

date: 2018-01-27
---

During my first semester at NYU, I took a class on [predictive analytics](https://en.wikipedia.org/wiki/Predictive_analytics). We covered everything from the [data mining project life cycle](https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining), understanding and preprocessing (noisy) data sets, [dimensionality reduction](https://en.wikipedia.org/wiki/Principal_component_analysis), feature selection, data clustering and classification algorithms, to mining association rules and getting some hands-on experience with large-scale data analytics frameworks, such as [MapReduce](https://en.wikipedia.org/wiki/MapReduce) in [Hadoop](http://hadoop.apache.org/) and [Apache Spark](https://spark.apache.org/). 

---

Throughout the semester, we also designed and implemented a complete text mining pipeline in Java. We started by vectorizing a collection of news articles using [term frequency-inverse document frequency (tf-idf)](https://en.wikipedia.org/wiki/Tf%E2%80%93idf). We then used [k-means clustering](https://en.wikipedia.org/wiki/K-means_clustering) in combination with measuring the [cosine similarity](https://en.wikipedia.org/wiki/Cosine_similarity) between the document vectors to cluster the articles based their content and semantic similarity. Finally, we implemented the [k-nearest neighbors algorithm (k-NN)](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm) to assign previously unseen documents to the clusters we had established in step two.

The only existing libraries I used were [JAMA](https://math.nist.gov/javanumerics/jama/) for the [singular-value decomposition (SVD)](https://en.wikipedia.org/wiki/Singular-value_decomposition) and [Stanford CoreNLP](https://stanfordnlp.github.io/CoreNLP/) to preprocess the text documents. Everything else was implemented from scratch.

---

<a href="https://github.com/melanietosik/text-mining" class="pa3 tc ba br2 db">View project on GitHub &#x263A;&#xFE0E;</a>

---
