---
title:  How to get started in NLP
date:   2017-05-01
---

![displaCy][parsetree]{: .center-image }

[parsetree]: {{site.url}}/files/displacy.png "Dependency parse tree visualized by displaCy"

<br>
Somewhere I read that if you ever have to answer the same question twice, it's probably a good idea to turn it into a blog post. In keeping with this rule and to save my future self some time, here now my standard answer to the question: "My background is in (some or other) science, and I'm interested in learning NLP. Where do I start?"

Before you dive in, please note that the list below is really just a very general starting point (and likely incomplete). To help navigate the flood of information, I added short descriptions and difficulty estimates in brackets. Basic programming skills (e.g. in Python) are recommended.

---

## Online courses

- [Dan Jurafsky & Chris Manning: Natural Language Processing](https://www.youtube.com/watch?v=nfoudtpBV68&list=PL6397E4B26D00A269)<br> [great intro video series]

- [Stanford CS224d: Deep Learning for Natural Language Processing](http://cs224d.stanford.edu/syllabus.html)<br> [more advanced ML algorithms, deep learning, and NN architectures for NLP]

- [Coursera: Introduction to Natural Language Processing](https://www.coursera.org/learn/natural-language-processing)<br> [intro NLP course offered by the University of Michigan]

---

## Libraries and open source

- [spaCy](https://spacy.io/)<br> [Python; emerging open-source library with [fantastic usage examples](https://spacy.io/usage/spacy-101), API documentation, and demo applications]

- [Natural Language Toolkit (NLTK)](http://www.nltk.org/)<br> [Python; practical intro to programming for NLP, mainly used for [teaching](http://www.nltk.org/book/)]

- [Stanford CoreNLP](https://stanfordnlp.github.io/CoreNLP/)<br> [Java; high-quality analysis toolkit]

---

## Active blogs

- [natural language processing blog](https://nlpers.blogspot.com/) by Hal Daumé

- [Language Log](http://languagelog.ldc.upenn.edu/nll/) by Mark Liberman

- [Google Research blog](https://research.googleblog.com/)

- [Explosion AI blog](https://explosion.ai/blog/) 

---

## Books

- [Speech and Language Processing](https://web.stanford.edu/~jurafsky/slp3/) by Daniel Jurafsky and James H. Martin<br> [classic NLP textbook that covers all the basics, 3rd edition in progress]

- [Foundations of Statistical Natural Language Processing](https://nlp.stanford.edu/fsnlp/) by Chris Manning and Hinrich Schütze<br> [more advanced, statistical NLP methods]

- [Introduction to Information Retrieval](https://nlp.stanford.edu/IR-book/) by Chris Manning, Prabhakar Raghavan and Hinrich Schütze<br> [excellent reference on ranking/search]

- [Neural Network Methods in Natural Language Processing](https://www.amazon.com/Network-Methods-Natural-Language-Processing/dp/1627052984) by Yoav Goldberg<br> [deep intro to NN approaches to NLP, [primer here](http://u.cs.biu.ac.il/~yogo/nnlp.pdf)]

---

## Miscellaneous

- [How to build a word2vec model in TensorFlow](https://www.tensorflow.org/versions/master/tutorials/word2vec/index.html)<br> [tutorial]

- [Deep Learning for NLP resources](https://github.com/andrewt3000/dl4nlp)<br> [overview of state-of-the-art resources for deep learning, organized by topic]

- [Last Words: Computational Linguistics and Deep Learning --  A look at the importance of Natural Language Processing.](http://mitp.nautil.us/article/170/last-words-computational-linguistics-and-deep-learning) by Chris Manning<br> [article]

- [Natural Language Understanding with Distributed Representation](https://github.com/nyu-dl/NLP_DL_Lecture_Note/blob/master/lecture_note.pdf) by Kyunghyun Cho<br> [self-contained lecture note on ML/NN approaches to NLU]

- [Bayesian Inference with Tears](http://www.isi.edu/natural-language/people/bayes-with-tears.pdf) by Kevin Knight<br> [tutorial workbook]

- [Association for Computational Linguistics](http://aclanthology.info/) (ACL)<br> [journal anthology]

- [Quora: How do I learn Natural Language Processing?](https://www.quora.com/How-do-I-learn-Natural-Language-Processing)

---

## DI(WH)Y projects and data sets

![diwhy][comic]{: .center-image }

[comic]: {{site.url}}/files/comic.png "http://gunshowcomic.com/"

---

A thorough [list of publicly available NLP data sets](https://github.com/niderhoff/nlp-datasets) has already been created by Nicolas Iderhoff. Beyond these, here are some projects I can recommend to any NLP novice wanting to get their hands dirty:

- Implement a [part-of-speech (POS) tagger](https://en.wikipedia.org/wiki/Part-of-speech_tagging) based on a [hidden Markov model](https://en.wikipedia.org/wiki/Hidden_Markov_model) (HMM)

- Implement the [CYK algorithm](https://en.wikipedia.org/wiki/CYK_algorithm) for parsing [context-free grammars](https://en.wikipedia.org/wiki/Context-free_grammar)

- Implement [semantic similarity](https://en.wikipedia.org/wiki/Semantic_similarity) between two given words in a collection of text, e.g. [pointwise mutual information](https://en.wikipedia.org/wiki/Pointwise_mutual_information) (PMI)

- Implement a [Naive Bayes classifier](https://en.wikipedia.org/wiki/Naive_Bayes_classifier) to [filter spam](https://en.wikipedia.org/wiki/Naive_Bayes_spam_filtering)

- Implement a [spell checker](https://en.wikipedia.org/wiki/Spell_checker) based on [edit distances](https://en.wikipedia.org/wiki/Edit_distance) between words

- Implement a [Markov chain](https://en.wikipedia.org/wiki/Markov_chain) text generator

- Implement a [topic model](https://en.wikipedia.org/wiki/Topic_model) using [latent Dirichlet allocation](https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation) (LDA)

- Use [word2vec](https://code.google.com/archive/p/word2vec/) to generate word embeddings from a large text corpus, e.g. [Wikipedia](https://en.wikipedia.org/wiki/Wikipedia:Database_download)

- Use [k-means](https://en.wikipedia.org/wiki/K-means_clustering) to cluster [tf-idf](https://en.wikipedia.org/wiki/Tf%E2%80%93idf) vectors of text, e.g. news articles

---

## NLP on social media

- Twitter: [List of NLPers](https://twitter.com/jasonbaldridge/lists/nlpers) by Jason Baldrige and `#nlproc`

- Reddit: `r/LanguageTechnology`

---

