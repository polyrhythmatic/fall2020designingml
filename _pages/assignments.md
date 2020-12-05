---
layout: default
permalink: /assignments
---

# Assignments

For all readings unless otherwise noted, please write down two non "yes or no" questions and type them into the Google doc I've shared with you. Be prepared to discuss the questions/readings in class.

## Week 4 (due 12/11)

No assignments this week - please work on your final

## Week 4 (due 12/4)

* Read
  * [Excavating AI](https://www.excavating.ai/)
  * [Dimensionality-Reduction Algorithms
for Progressive Visual Analytics](https://www.researchgate.net/publication/331314858_Dimensionality-Reduction_Algorithms_for_Progressive_Visual_Analytics) - just summary and introduction

The Final (due 12/18)

Choose an image or text data set to explore. This can be an existing API or data set such as a digital museum collection, but it could also be a data set of your own creation such as a website that you scrape or collection of your own photos. Using the tools we covered so far, create an analysis of the visual topology of this collection. When using machine learning to look with a macro lens, what patterns emerge? What narratives are newly exposed with these techniques?

Be sure to collect at least 500-600 data points (images, paragraphs, articles, reviews etc) in order to have enough to analyze. The final deliverable for this class will be a series of images, along with a quick in-class presentation. If you are comfortable with web development, please feel free to create something larger for the midterm.

Presenting the project: 

If there are no group projects then we will have less than 10 minutes per person to present, "pecha kucha" style. I will be expecting a fairly concrete and succinct presentation of about 5 minutes.

Metrics for grading:
* 25% - Originality of concept - Does the project explore an original and novel concept?
* 25% - Fit and finish - Is the project finished? Was there clearly thought put into this?
* 25% - Theme - Did the project follow the prompt?
* 25% - Presentation - Is the presentation coherent and thoughtful?

Due 12/18:

Before next class, email me:

* One paragraph describing what your project explore
* If applicable, a link to the data set you will be using
* The name of the data set you will be using
* Is it a group project? Who is involved, and what part will they take?
* If desired, sign up for office hours to discuss


## Week 3 (due 11/20)

* Read
  * [Anatomy of an AI System](https://anatomyof.ai/)
  * [Using Artificial Intelligence to Augment Human Intelligence](https://distill.pub/2017/aia/)

* Watch (optional)
  * [Vectors, what even are they?](https://www.youtube.com/watch?v=fNk_zzaMoSs)
  * [Vectors - The Nature of Code](https://www.youtube.com/watch?v=mWJkvxQXIa8)
  * [Vector Math - The Nature of Code](https://www.youtube.com/watch?v=s6b1_3bNCxk)
  * [Vector Math II - The Nature of Code](https://www.youtube.com/watch?v=uHusbFmq-4I)

* Code
  * Review the in class jupyter notebook
  * Try implementing your own classifier using one of the other [Scikit learn toy datasets](https://scikit-learn.org/stable/datasets/index.html#toy-datasets). Google around for ideas. This will not be graded or collected.

## Week 2 (due 11/13)
* Read
  * [The Myth of AI by Jaron Lanier](https://www.edge.org/conversation/jaron_lanier-the-myth-of-ai) (just read article not comments or video)
  * [More States Opting To ‘Robo-Grade’ Student Essays By Computer](https://www.npr.org/2018/06/30/624373367/more-states-opting-to-robo-grade-student-essays-by-computer)
  * [Don’t Call AI “Magic” by M.C. Elish](https://points.datasociety.net/dont-call-ai-magic-142da16db408)

* Code
  * Review the in class jupyter notebook
  * If you are having a hard time with Python, try doing all the "Learn the Basics" section at [learnpython.org](https://www.learnpython.org/)
  * I recommend also picking up Learn Python 3 the Hard Way if you like learning from printed books

* Watch (at least one)
  * [Vectors, what even are they?](https://www.youtube.com/watch?v=fNk_zzaMoSs)
  * [Vectors - The Nature of Code](https://www.youtube.com/watch?v=mWJkvxQXIa8)
  * [Vector Math - The Nature of Code](https://www.youtube.com/watch?v=s6b1_3bNCxk)
  * [Vector Math II - The Nature of Code](https://www.youtube.com/watch?v=uHusbFmq-4I)

## Week 1 (due 2/6)
* Read
  * [Artificial Intelligence Hits the Barrier of Meaning by Melanie Mitchell](https://www.nytimes.com/2018/11/05/opinion/artificial-intelligence-machine-learning.html)
  * [Ways to think about machine learning by Benedict Evans](https://www.ben-evans.com/benedictevans/2018/06/22/ways-to-think-about-machine-learning-8nefy)
  * [Towards a Poetics of Artificial Superintelligence by Nora N. Khan](https://medium.com/after-us/towards-a-poetics-of-artificial-superintelligence-ebff11d2d249)

* Code

Follow the instructions below to install Homebrew, Python, and Jupyter notebook

Using the terminal, install [Homebrew](https://brew.sh/)

First, make sure you have Xcode command-line tools installed. Note - this is *not* the Xcode editor. These are separate tools that run from your command line. Run the commands below (without the `$` at the beginning of the line):

```console
$ xcode-select --install
```

Next, we install Homebrew by running the following command:

```console
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Run the following command once you’re done to ensure Homebrew is installed and working properly:

```console
$ brew doctor
```

Next, we install Python 

```console
$ brew install python
```

Check your install with the following command

```console
$ python --version
```

It should say report a version of python 3 or higher

Next we can use pip, pythons package manager, to install jupyter notebook and other dependencies:

```console
$ pip3 install jupyterlab
$ pip3 install matplotlib
```

We then run the command below to open a jupyter notebook. Make sure you are in the correct directory when you run this command.

```console
$ jupyter notebook
```

Please let me know on slack if you are having a hard time with this and I can try and work through it with you before Friday's class.

