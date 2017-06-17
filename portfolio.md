---
layout: page
title: portfolio
permalink: /portfolio/
---

# Edit distances and sequence alignment

During my senior year, I finally took a class on advanced C++. Surprisingly enough, it didn't seem nearly as hard as the first one I had to struggle through a few years ago, and I ended up having a lot of fun with it.

As final project, I decided to work on edit distances and implement the [Wagner–Fischer algorithm](https://en.wikipedia.org/wiki/Wagner%E2%80%93Fischer_algorithm) as an instance of dynamic programming. Later on, I expanded the project to also cover the [Needleman-Wunsch algorithm](https://en.wikipedia.org/wiki/Needleman%E2%80%93Wunsch_algorithm) for global sequence alignment.

[[GitHub](https://github.com/melanietosik/cpp2/tree/master/sda)]


# Semantic role labeling using linear-chain CRF

My very last undergrad project for a class on advanced language modeling, where we discussed the theoretical foundations of [hidden Markov models](https://en.wikipedia.org/wiki/Hidden_Markov_model), the [Viterbi](https://en.wikipedia.org/wiki/Viterbi_algorithm) and [EM algorithms](https://en.wikipedia.org/wiki/Expectation%E2%80%93maximization_algorithm), [log-linear models](https://en.wikipedia.org/wiki/Log-linear_model), [maximum entropy models](https://en.wikipedia.org/wiki/Principle_of_maximum_entropy#Maximum_entropy_models) (MEMMs), and as well as [conditional random fields](https://en.wikipedia.org/wiki/Conditional_random_field) (CRFs).

[[Paper]({{ site.baseurl }}/assets/srl.pdf)] [[GitHub](https://github.com/melanietosik/srl)]


# String to semantic graph alignment

For my undergrad thesis, I started working on semantic parsing: the problem of mapping natural language strings to meaning representations. In order to train a semantic parser for English to [Abstract Meaning Representation](https://www.amr.isi.edu/) (AMR), we first need to know which phrases in the input sentence invoked which concepts in the corresponding AMR graph. The project aimed at building an English/AMR aligner to solve this task automatically.

[[Inspiration](http://www.isi.edu/natural-language/mt/amr_eng_align.pdf)] [[Thesis]({{ site.baseurl }}/assets/thesis.pdf)] [[GitHub](http://github.com/melanietosik/thesis_code)]


# Dish AI

At [WayBlazer](http://www.wayblazer.ai/), our product manager kept joking about how we needed a "dish AI" to review our catered lunches every day. This is it, featuring a preprocessed review data set, topic models, a Markov chain generator, and a Flask API to put it all together!

[[GitHub](http://github.com/melanietosik/dish_ai)]


# Semantic dependency graph parsing

For a class on semantic dependency graph parsing, I wrote a short script that computes statistics for semantic dependency graphs and generates plots for the distribution of words per [indegree and outdegree](http://en.wikipedia.org/wiki/Directed_graph#Indegree_and_outdegree). As final project, I submitted a comprehensive review on [Abstract Meaning Representation](href="http://amr.isi.edu/) (AMR), a set of English sentences paired with simple, readable semantic representations.

[[Paper]({{ site.baseurl }}/assets/amr.pdf)] [[GitHub](https://github.com/melanietosik/dp1)]


# Research internship at Textkernel

In 2014, I was a research intern at [Textkernel](http://www.textkernel.com/), where we explored new methods of improving resume parsing for multi-lingual documents.

In order to extract structured information in the form of specific phrases like *name* or *address*, we adopted the probabilistic [conditional random fields](http://en.wikipedia.org/wiki/Conditional_random_field) (CRF) framework. In addition, we experimented with a novel approach that integrates [continuous vector representations](https://code.google.com/p/word2vec/) of words as input features for such a model.

[[Paper](http://www.aclweb.org/anthology/W15-1517)] [[Interview](http://www.textkernel.com/2014/12/internships-at-textkernel-melanie-tosik/)] [[Internship report]({{ site.baseurl }}/assets/report_tosik_textkernel.pdf)]


# Word meaning in context

For a really great class on [distributional semantics](http://en.wikipedia.org/wiki/Distributional_semantics), I presented a paper on "Measuring Distributional Similarity in Context" ([Dinu and Lapata, 2010](http://www.aclweb.org/anthology/D10-1113)).

In a nutshell, they attempt to model the intuition that word meaning is represented as a probability distribution over a set of latent senses, and thus modulated by context. They employ two different models: the first based on [non-negative matrix factorization](http://en.wikipedia.org/wiki/Non-negative_matrix_factorization) (NMF), and the second implementing [Latent Dirichlet Allocation](http://en.wikipedia.org/wiki/Latent_Dirichlet_allocation) (LDA).

[[Paper]({{ site.baseurl }}/assets/dist_sem.pdf)] [[Slides]({{ site.baseurl }}/assets/dinulapata.pdf)] (in German)


# Lexical semantics

I studied abroad and [learned some linguistics](http://www.socsci.ulster.ac.uk/irss/linguistics.html):

> Consider an example where a zombie has died and been reanimated, and John drowns him.

Presentation slides may or may not help to get to the bottom of this!

[[Slides]({{ site.baseurl }}/assets/beavers.pdf)]


# Word similarity

Shortly after I learned that computational semantics was a thing, I implemented word similarity according to [Dekang Lin (1998)]({{ site.baseurl }}/assets/lin.pdf).

[[GitHub](http://github.com/melanietosik/linsim)]


# Sentence comprehension

I took some classes on [psycholinguistics](http://www.uni-potsdam.de/humfak/hum-forschungsschwerpunkte/forschungscluster-sprache.html), where I presented a range of interesting papers including "Expectation-based syntactic comprehension" ([Levy, 2008](http://idiom.ucsd.edu/~rlevy/papers/levy-2008-cognition.pdf)) and "Dependency Locality Theory" (DLT) ([Gibson, 2000](http://tedlab.mit.edu/tedlab_website/researchpapers/Gibson_2000_DLT.pdf)). Slides below!

[[Levy]({{ site.baseurl }}/assets/levy.pdf)] [[Gibson]({{ site.baseurl }}/assets/gibson.pdf)]
