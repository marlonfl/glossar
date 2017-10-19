# glossar
Glossar - A computer science-domain-specific question answering system.

The domain is determined by the sources used. For now I'm planning on using Wikipedia and StackOverflow as primary sources.

Answers will be short summarizations of the given topic, I also plan providing links to papers that might be of interest for the given topic.

I won't process the question a whole lot, I don't want to build a general question answering system. Question format will be "What is + topic?" so I don't have to do any NLP on the question itself.

I plan on using some ML algorithm to extract answer senteces from relevant documents extracted from the sources and I hope to condense them into a single answer that makes sense.

The first real application of this will be a Machine Learning Glossary that I'll put up somewhere so people (and I) can learn easier.

I might also build a simple speech recognizer for this in the end. Shouldn't be too much of a problem since basically only 1 word has to be recognized - the topic in question.
