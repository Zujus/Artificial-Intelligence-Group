# Definition of AI

Discussion started in [the Facebook group](https://www.facebook.com/groups/artificialintelligence.lt/permalink/1698578623535968/).

The overall best already publicly written definition is the first two paragraphs by Amazon in [an article on Machine Learning on AWS](https://aws.amazon.com/machine-learning/what-is-ai/).

But what does a modern company in 2018 have to do to be considered doing Artificial Intelligence?
The answer is: it has to work with [second wave AI technologies and/or develop third wave AI technologies](https://youtu.be/-O01G3tSYpU?t=3m43s), see the John Launchbury section below for summary.
That's it.
It's the simplest model of all of them in the sections below.
You can stop reading now.

Why are the first wave AI technologies excluded from the definition?
It is illogical!
Because: 1) all software companies are using them. 2) Marvin Minsky once said "It often does more harm than good to force definitions on things we don't understand."
So a part of AI is very playfully excluded from the definition of (a modern) AI.
Finally, there is [this one by Sheila McIlraith](http://www.teach.cs.toronto.edu/~csc384h/winter/Lectures/csc384w18-Lecture01-Intro.pdf):

> There will be no “ah ha” moment in which we say now we have “achieved artificial intelligence”.
> It will creep up on us.
> Systems will adapt to users in the most natural and subtle ways.
> And society will adapt to the “new normal”.

First wave is currently the "new normal".

Concretely, using the list of second wave AI technologies taught at [MIT](https://ai6034.mit.edu/wiki/index.php?title=Reference_material_and_playlist), __a company in 2018 is considered to do AI if it works with these methods: nearest neighbor learning, decision tree learning, neural net learning, deep neural net learning, genetic algorithms, sparse trees, support-vector machines, bayesian inference, boosting and similar__.
Goal trees, rule based expert systems, search, games, constraint programming and similar do not count!

Wikipedia has longer definitions, but if this subject is new to you, it can help in mapping out the big picture: [Artificial Intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence), [Artificial general intelligence / Strong AI / Full AI / General AI / "true" AI](https://en.wikipedia.org/wiki/Artificial_general_intelligence), [Weak AI / Narrow AI / Applied AI](https://en.wikipedia.org/wiki/Weak_AI) and [AI-complete / AI-complete](https://en.wikipedia.org/wiki/AI-complete).

## Marvin Minsky on definitions

In 1968:
> Artificial intelligence is the science of making machines do things that would require intelligence if done by men.

In 1985:
> It often does more harm than good to force definitions on things we don't understand. Besides, only in logic and mathematics do definitions ever capture concepts perfectly. The things we deal with in practical life are usually too complicated to be represented by neat, compact expressions. Especially when it comes to understanding minds, we still know so little that we can't be sure our ideas about psychology are even aimed in the right directions. In any case, one must not mistake defining things for knowing what they are.

## John McCarthy in [an interview](http://jmc.stanford.edu/artificial-intelligence/what-is-ai/index.html):

>It is the science and engineering of making intelligent machines, especially intelligent computer programs. It is related to the similar task of using computers to understand human intelligence, but AI does not have to confine itself to methods that are biologically observable.

## Pedro Domingos presenting [The Five Tribes of Machine Learning And What You Can Take from Each](https://learning.acm.org/webinar_pdfs/PedroDomingos_FTFML_WebinarSlides.pdf)

The 8th slide contains "The Five Tribes of Machine Learning":

| Tribe          | Origins              | Master Algorithm        |
| -------------- | -------------------- | ----------------------- |
| Connectionists | Neuroscience         | Backpropagation         |
| Evolutionaries | Evolutionary biology | Genetic programming     |
| Bayesians      | Statistics           | Probabilistic inference |
| Analogizers    | Psychology           | Kernel machines         |
| Symbolists     | Logic, philosophy    | Inverse deduction       |

## John Launchbury presenting [A DARPA Perspective on Artificial Intelligence](https://www.youtube.com/watch?v=-O01G3tSYpU) - three waves of AI technology

* First wave is characterized by using knowledge that is handcrafted. It is about encoding logical rules in a computer program by an expert human.
* Second wave is characterized by using knowledge that is statistically learned. It is about starting to incorporate probabilistic techniques, these days called machine learning.
* Third wave (future) will be characterized by contextual adaptation. It is about building systems that can be trained from one or two examples and themselves construct explanatory models for classes of real world phenomena.

## Patrick Henry Winston in [an article "The next 50 years: A personal view"](https://dspace.mit.edu/handle/1721.1/108137)

> I conclude by suggesting, optimistically, that a genuine computational theory of human intelligence will emerge in the next 50 years if we stick to the right, biologically inspired questions, and work toward biologically informed models.

## First lecture in [Massachusetts Institute of Technology (6.034 - Artificial Intelligence - Fall 2017)](https://ai6034.mit.edu/wiki/index.php?title=Reference_material_and_playlist)

It is called "What it's all about", but the content is not publicly available.
Thus use the reference material to decide what they define as a set of artificial intelligence methods.
The sequence of reference material indicates that the definition of AI is the same as that by John Launchbury:

* They have goal trees, rule based expert systems, search, games, constraint programming as the first wave of handcrafted knowledge.
* For the second wave there is nearest neighbor learning, decision tree learning, neural net learning, deep neural net learning, genetic algorithms, sparse trees, support-vector machines, bayesian inference and boosting.
* For the third wave of contextual adaptation technologies they mostly plan to develop systems using biologically informed (3 M's - internal Mental models for stories; Math; Music) models.

They also have a future-focused course [6.803/6.833 - The Human Intelligence Enterprise - Spring 2018](http://courses.csail.mit.edu/6.803/) and [Genesis](http://groups.csail.mit.edu/genesis/) research group.
Mostly this is inspired by and continuation of the work by Marvin Minsky, of which there is a good accessible presentation in his book [The Emotion Machine](http://www.simonandschuster.com/books/The-Emotion-Machine/Marvin-Minsky/9780743276641).

## [First lecture](http://www.cs.cmu.edu/~15381-f17/intro%20to%20AI.pptx) in Carnegie Mellon University (15-381/681 - Artificial Intelligence: Representation and Problem Solving - Fall 2017)

> Artificial Intelligence is the development and study of computing systems that address a problem typically associated with some form of intelligence.

## [First lecture](http://www.seas.upenn.edu/~cis521/Lectures/ClassIntro-2017-6up.pdf) in University of Pennsylvania (CIS521 - Introduction to Artificial Intelligence - Fall 2017)

> Two Approaches to AI:
> 1) Logical representations;
> 2) Statistical models.

## [First lecture](http://www.teach.cs.toronto.edu/~csc384h/winter/Lectures/csc384w18-Lecture01-Intro.pdf) in University of Toronto (CSC384 - Introduction to Artificial Intelligence - Winter 2018)

> How to achieve intelligent behaviour through computational means.
> AI tries to understand and model intelligence as a computational process. Thus we try to construct systems whose computation achieves or approximates the desired notion of intelligence.

> Broad view of AI:

> * Perception: vision, speech understanding, etc.
> * Machine Learning, Neural network
> * Natural language understanding
> * Robotics
> * Reasoning and decision making
>     * Knowledge representation
>     * Reasoning (logical, probabilistic)
>     * Decision making (search, planning, decision theory)

## The classical book [Artificial Intelligence book by Russel and Norvig](https://www.amazon.com/Artificial-Intelligence-Modern-Approach-3rd/dp/0136042597)

It is used by at least these universities:

* [Massachusetts Institute of Technology (6.034 - Artificial Intelligence - Fall 2017)](https://ai6034.mit.edu/wiki/index.php?title=Reference_material_and_playlist)
* [University of Toronto (CSC384 - Introduction to Artificial Intelligence - Winter 2018)](http://www.teach.cs.toronto.edu/~csc384h/winter/lectures.html)
* [University of Oxford (Intelligent Systems: 2017-2018)](https://www.cs.ox.ac.uk/teaching/courses/2017-2018/intellsystems/index.html)
* [Carnegie Mellon University (15-381/681 - Artificial Intelligence: Representation and Problem Solving - Fall 2017)](http://www.cs.cmu.edu/~15381-f17/)
* [Stanford University (CS221 - Artificial Intelligence: Principles and Techniques - Autumn 2017-2018)](http://www.stanford.edu/class/cs221/)
* [University of Cambridge (Artificial Intelligence: 2017-2018)](https://www.cl.cam.ac.uk/teaching/1718/ArtInt/)

It defines AI as a field that tries to "build intelligent entities", not only to understand them.

It tells that AI has a huge variety of subfields and is a truly universal field.

It uses four views of AI model to classify the AI systems:

![Four Views of AI](https://image.slidesharecdn.com/01-intro1-120330194216-phpapp01/95/01-intro1-12-728.jpg)
