# Antisemitism Datathon 2020

(C) 2020 by [Damir Cavar] and [Günther Jikeli]

The information and code examples are licensed under the Apache License Version 2.0.


This is project material for the [Antisemitism Datathon and Hackathon 2020](https://isca.indiana.edu/news-events/Antisemitism%20on%20Social%20Media%20Workshops%20in%20May%202020.html) at [Indiana University at Bloomington].

This [Datathon and Hackathon](https://isca.indiana.edu/news-events/Antisemitism%20on%20Social%20Media%20Workshops%20in%20May%202020.html) is a collaborative project of [Günther Jikeli] from the [Institute for the Study of Contemporary Antisemitism](https://isca.indiana.edu/) and [Damir Cavar]'s [NLP-Lab.org] at [Indiana University at Bloomington]!


## NLP API and RESTful Microservices

We provide an NLP pipeline with detailed linguistic analysis: tokenization, lemmatization, splitting text into sentences, part-of-speech tagging, named entity annotation, dependency parsing, constituent parsing, sentiment detection, and coreference and anaphora resolution:

- [NLP Pipeline as RESTful API](https://jnlp.semantic-tech.com/) (provided through the courtesy of [Semiring Inc.])

This pipeline is an integration of [RESTful Microservices] that take as input some text and return a [JSON-NLP] formated output. This service requires a login and password. We will share this with you during the meetings.

The linguistic annotations enable modeling of classifiers using deeper linguistic analysis.

This folder contains example code in various languages to communicate with the API using RESTful API GET and POST calls.


### Python Example


### JavaScript Example


### Go Example

