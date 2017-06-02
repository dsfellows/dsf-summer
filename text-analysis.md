# Intro to Computational Text Analysis


## Computational text analysis: the big picture

+ How can we get a sense of what's in a large corpus of text without reading every word? Or: how can we re-see the contents of a text or corpus of texts we've read?
+ Distant reading?
+ Applications in humanities, social sciences


## A corpus of Philadelphia-related texts from the 19th century

[Download, unzip, and take a look at the contents.](https://github.com/dsfellows/dsfellows/blob/master/week_9_materials.zip)


## Voyant

[voyant-tools.org](http://voyant-tools.org/)

+ Stopwords
  + (Compare stopword lists of different lengths [here](http://www.ranks.nl/stopwords/))
+ Search with regular expressions


## Topic modeling

[Topic modeling tool - different versions for Mac and PC](https://github.com/senderle/topic-modeling-tool)

[Instructions for running the topic modeling tool](https://senderle.github.io/topic-modeling-tool/documentation/2017/01/06/quickstart.html)

**Make sure you include the metadata.csv file (in the zip file you downloaded).**


## What is topic modeling?

+ A form of computational text analysis that identifies clusters of words that are likely to occur together using Bayesian probability
+ Imagines that each text is composed of a finite set of "topics" or discourses. Zoe Borovsky's [analogy](http://miriamposner.com/blog/very-basic-strategies-for-interpreting-results-from-the-topic-modeling-tool/): like sticking together lumps of play-doh. Topic modeling reverse-engineers the text and tries to figure out what it's made of
+ This isn't necessarily a literal truth about how texts are composed; it may not even be a good model of how societal influences or discourses help to form texts. But it gives us a way to re-think or re-see the contents of a text/corpus

![Visual representation of topic modeling](https://github.com/dsfellows/dsfellows/blob/master/Blei_topicmodel.png)

*A visual representation of topic modeling by [David M. Blei](http://www.cs.princeton.edu/~blei/papers/Blei2012.pdf).*

+ Running a topic model multiple times will give you different results each time

> [W]e instruct the computer to pick topics for us, and it begins with a series of blind guesses, assigning words to bins at random. The computer knows a warehouse full of word bins exists, but it cannot see inside it. The topic model is the computer’s attempt at inferring the contents of each bin by looking at each document and working backwards to the topic bins it likely drew from. The computer starts from the assumption that if several documents contain the same groups of words, those words likely form a ‘topic’. As the computer scans through the text over and over again, it reorganizes its initially random bins into closer and closer approximations of what it guesses the “real” topic bins must look like. Internally, the computer is optimizing for this problem: given a distribution of words over an entire collection of documents, what is the probability that this distribution of words within a document belong to a particular topic?

> This is a Bayesian approach to probability. Thomas Bayes was an 18th century clergyman who dabbled in mathematics. He was interested in problems of conditional probabilities, in light of prior knowledge. The formula which now bears Bayes’ name depends on assigning a prior probability, and then re-evaluating that probability in the light of what it finds. As the computer goes through this process over and over for each word in the collection, it changes its assumptions about the distribution. [source](http://www.themacroscope.org/?page_id=553)


## Additional resources

+ [JSTOR topicgraph](https://labs.jstor.org/topicgraph/): beta version of a tool that topic models scholarly monographs and visualizes the results; also possible to run on your own documents
+ ["Topic Modeling: A Basic Introduction"](http://journalofdigitalhumanities.org/2-1/topic-modeling-a-basic-introduction-by-megan-r-brett/) by Megan R. Brett
+ ["Topic Modeling Made Just Simple Enough"](https://tedunderwood.com/2012/04/07/topic-modeling-made-just-simple-enough/) by Ted Underwood (includes an explanation of the math behind topic modeling geared toward people with less of a math/CS background)
+ [A more allegorical explanation of topic modeling](http://www.matthewjockers.net/2011/09/29/the-lda-buffet-is-now-open-or-latent-dirichlet-allocation-for-english-majors/) by Matt Jockers
+ [Historian's Macroscope writeup](http://www.themacroscope.org/?page_id=553) on topic modeling, including some discussion of why multiple runs generate different results and instructions for using pivot tables to analyze results
