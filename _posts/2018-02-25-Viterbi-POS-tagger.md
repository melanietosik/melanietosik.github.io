---
title: Viterbi part-of-speech (POS) tagger

date: 2018-02-25
---

For my natural language processing (NLP) class, we were asked to implement and train a [part-of-speech (POS) tagger](https://en.wikipedia.org/wiki/Part-of-speech_tagging), as described in the 3rd edition of ["Speech and Language Processing"](https://web.stanford.edu/~jurafsky/slp3/10.pdf) (Jurafsky and Martin). I actually distinctly remember a very similar assignment during my undergraduate NLP class, where I felt so overwhelmed with the data structures and implementation details of the Viterbi algorithm that I ended up skipping the assignment entirely (which was allowed, one time). I've always been meaning to revisit this problem since, so I was really excited about finally getting a chance to do so.

---

In a nutshell, a POS tagger attempts to read in some text in a given language and assign a POS tag to each word (or token), such as _noun_, _verb_, _adjective_, etc. (although in practice these are usually divided into [more fine-grained categories](https://www.ling.upenn.edu/courses/Fall_2003/ling001/penn_treebank_pos.html)). This is a hard problem because many (if not most) English words are ambiguous in their POS. For example, the word "experience" frequently occurs as both a noun and a verb, "abstract" can be a noun and an adjective, and so on.

In general, there are two parts to building a (supervised) POS tagger: training and decoding. For this project, training was done using a [hidden Markov model (HMM)](https://en.wikipedia.org/wiki/Hidden_Markov_model), which essentially involves estimating transition and emission probabilities for the hidden states (POS tags) that correspond to each observation (token) in the annotated training data. To decode new observations, we can then use the [Viterbi algorithm](https://en.wikipedia.org/wiki/Viterbi_algorithm), which computes the most likely sequence of POS tags given the current input sequence/sentence.

Both the HMM and the Viterbi algorithm are relatively straightforward to implement. The major challenge is how to deal with previously unseen observations for which no probabilities have been observed in the training data. [Additive smoothing](https://en.wikipedia.org/wiki/Additive_smoothing) is one standard way to deal with unknown words, but there are many more advanced techniques out there that might yield even better results (such as the Good-Turing method, Katz's backoff, or smoothing by linear interpolation).

---

<a href="https://github.com/melanietosik/viterbi-pos-tagger" class="pa3 tc ba br2 db">View project on GitHub &#x263A;&#xFE0E;</a>

---
