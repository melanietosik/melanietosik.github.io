---
title: NLP with representation learning
date: 2018-12-14
---

This fall semester, I finally got into "Natural Language Processing with Representation Learning", a popular course taught by [Kyunghyun Cho](http://www.kyunghyuncho.me/) at NYU. I remember reading the lecture note a few years ago and feeling really inspired to learn, so this was a particularly excited class for me.

If you're unfamiliar with the topic, I highly recommend taking a look at the course materials yourself. The [lecture note is available on GitHub](https://github.com/nyu-dl/NLP_DL_Lecture_Note/blob/master/lecture_note.pdf), and the [syllabus is open-source](https://docs.google.com/document/d/1o0TTWocbkqPa9qsTCXnEFXf3NZzwZLLLSw7SSZmNla8/edit#) as well.

---

Throughout the course, I completed two large programming assignments:

- ["Bag-of-words (BOW) sentiment classification"]({{site.url}}/files/bow_document_classification.pdf)

<a href="https://github.com/melanietosik/bow-sentiment-classifier" class="pa1 tc ba br2 db">View sentiment project on GitHub &#x263A;&#xFE0E;</a>

- ["RNN/CNN-based natural language inference"]({{site.url}}/files/CNN_RNN_nl_inference.pdf)

<a href="https://github.com/melanietosik/nl-inference" class="pa1 tc ba br2 db">View inference project on GitHub &#x263A;&#xFE0E;</a>

---

For our final project, we had to build a sequence of neural machine translation systems for two language pairs, Vietnamese (Vi) &#8594;&#xFE0E; English (En) and Chinese (Zh) &#8594;&#xFE0E; English (En). Specifically, we implemented and evaluated the following model architectures:

- RNN based encoder-decoder without attention
- RNN based encoder-decoder with attention
- CNN-RNN encoder-decoder with attention

Our results were promising despite the limited amount of training data! You can read all about our work in our project report on ["RNN/CNN-based Neural Machine Translation for Vietnamese and Chinese to English"]({{site.url}}/files/nmt_final_project.pdf).

---

<a href="https://github.com/ds1011teamproject/translation" class="pa2 tc ba br2 db">View translation project on GitHub &#x263A;&#xFE0E;</a>

---
