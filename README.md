# Antisemitism Datathon 2020

(C) 2020 by [Damir Cavar] and [Guenther Jikeli]

The information and code examples are licensed under the Apache License Version 2.0.


This is project material for the [Antisemitism Datathon and Hackathon 2020](https://isca.indiana.edu/news-events/Antisemitism%20on%20Social%20Media%20Workshops%20in%20May%202020.html) at [Indiana University at Bloomington].

This [Datathon and Hackathon](https://isca.indiana.edu/news-events/Antisemitism%20on%20Social%20Media%20Workshops%20in%20May%202020.html) is a collaborative project of Günther Jikeli from the [Institute for the Study of Contemporary Antisemitism](https://isca.indiana.edu/) and [Damir Cavar]'s [NLP-Lab.org] at [Indiana University at Bloomington]!



## Relevant Links

- [Datathon and Hackathon 2020 Website](https://isca.indiana.edu/news-events/Antisemitism%20on%20Social%20Media%20Workshops%20in%20May%202020.html)


## Technologies

We provide an NLP pipeline with detailed linguistic analysis: tokenization, lemmatization, splitting text into sentences, part-of-speech tagging, named entity annotation, dependency parsing, constituent parsing, sentiment detection, and coreference and anaphora resolution:

- [NLP Pipeline as RESTful API](https://jnlp.semantic-tech.com/) (provided through the courtesy of [Semiring Inc.])

This pipeline is an integration of [RESTful Microservices] that take as input some text and return a [JSON-NLP] formated output. This service requires a login and password. We will share this with you during the meetings.

The linguistic annotations enable modeling of classifiers using deeper linguistic analysis.

In addition to that, we provide code examples for the following NLP and Machine Learning libraries, to develop probabilistic, neural, and/or symbolic classifiers for the corpus material:

- [spaCy]
- [Flair]
- [NLTK]
- [Tensorflow]
- [PyTorch]


## Data Sets and Formats

The Antisemitism Twitter corpus will be provided to you in a specific CSV format. We will also provide a CoNLL formated version of the data. These are formats that the different Machine Learning libraries for NLP mentioned above can read.

You might want to have a look at the different corpus or linguistic data formats:

- [CoNLL-X](https://www.aclweb.org/anthology/W06-2920.pdf)
- [CoNLL-U](https://universaldependencies.org/format.html)
- [spaCy JSON](https://spacy.io/usage/training)




[Damir Cavar]: https://www.linkedin.com/in/damircavar/ "Damir Cavar"
[Günther Jikeli]: https://isca.indiana.edu/about/faculty/jikeli-gunther.html "Günther Jikeli"
[Indiana University at Bloomington]: http://www.indiana.edu/ "IU Bloomington"
[spaCy]: https://spacy.io/ "spaCy"
[Flair]: https://github.com/flairNLP/flair "Flair"
[Tensorflow]: https://www.tensorflow.org/ "Tensorflow"
[PyTorch]: https://pytorch.org/ "PyTorch"
[Semiring Inc.]: https://semiring.com/ "Semiring Inc."
[NLTK]: https://www.nltk.org/ "Natural Language Toolkit"
[RESTful Microservices]: https://blog.dreamfactory.com/restful-api-and-microservices-the-differences-and-how-they-work-together/ "RESTful Microservices"
[JSON-NLP]: https://github.com/SemiringInc/JSON-NLP "JSON-NLP Annotation Standard"
