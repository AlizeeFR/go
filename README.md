_created & maintained by [@clarecorthell](http://bit.ly/clarecorthelltwitter), founding partner of [Luminant Data Science Consulting](http://bit.ly/luminantdata)_

<summary> Contents
<details>
  - [The Open-Source Data Science Masters](#the-open-source-data-science-masters)
  - [Contents](#contents)
  - [The Internet is Your Oyster](#the-internet-is-your-oyster)
  - [The Motivation](#the-motivation)
  - [An Academic Shortfall](#an-academic-shortfall)
  - [Ready?](#ready)
- [The Open Source Data Science Curriculum](#the-open-source-data-science-curriculum)
  - [A Note About Direction](#a-note-about-direction)
  - [Math](#math)
  - [Computing](#computing)
  - [Data Analysis](#data-analysis)
  - [Data Communication and Design](#data-communication-and-design)
    - [Python (Learning)](#python-learning)
    - [Python (Libraries)](#python-libraries)
    - [Datasets are now here](#datasets-are-now-here)
    - [R resources are now here](#r-resources-are-now-here)
  - [Data Science as a Profession](#data-science-as-a-profession)
  - [Capstone Project](#capstone-project)
  - [Resources](#resources)
    - [Read](#read)
    - [Watch & Listen](#watch--listen)
    - [Learn](#learn)
  - [Notation](#notation)
- [Contribute](#contribute)
  </details>
  </summary>
  
## The Open Source Data Science Curriculum

Start here.

**Intro to Data Science** / UW [Videos](https://github.com/datasciencemasters/go/issues/102)
 * *Topics:* Python NLP on Twitter API, Distributed Computing Paradigm, MapReduce/Hadoop & Pig Script, SQL/NoSQL, Relational Algebra, Experiment design, Statistics, Graphs, Amazon EC2, Visualization.

**Data Science** / Harvard [Videos](http://bit.ly/harvarddatasciencevideos) & [Course](http://bit.ly/harvarddatasciencecourse)
 * *Topics:* Data wrangling, data management, exploratory data analysis to generate hypotheses and intuition, prediction based on statistical methods such as regression and classification, communication of results through visualization, stories, and summaries.

**Data Science with Open Source Tools** [Book ```$27```](http://bit.ly/book-datasciencewithopensourcetools)
  * *Topics:* Visualizing Data, Estimation, Models from Scaling Arguments, Arguments from Probability Models, What you Really Need to Know about Classical Statistics, Data Mining, Clustering, PCA, Map/Reduce, Predictive Analytics
  * *Example Code in:* R, Python, Sage, C, Gnu Scientific Library
### Ethics in Machine Intelligence
Human impact is a first-class concern when building machine intelligence technology. When we build products, we deduce patterns and then reinforce them in the world. Ethics in any Engineering concerns understanding the sociotechnological impact of the products and services we are bringing to bear in the human world -- and whether they are reinforcing a future we all want to live in.
* [Index: Cultural Bias in Machine Intelligence](http://machinebias.org/)

<summary> Math and Problem-Solving
  <details>
### Math

* [What are some good resources for learning about numerical analysis? / Quora](http://www.quora.com/What-are-some-good-resources-for-learning-about-numerical-analysis)

#### **Linear Algebra & Programming**
 * Linear Algebra [Khan Academy / Videos](http://bit.ly/khanlinalg)
 * Linear Algebra / Levandosky [Stanford / Book ```$10```](http://amzn.to/1kIfmmI)
 * Linear Programming (Math 407) [University of Washington / Course](http://bit.ly/course-uw-linearprogramming)
 * The Manga Guide to Linear Algebra [Book ```$19```](http://amzn.to/1n4hM5l)
 * An Intuitive Guide to Linear Algebra [Better Explained / Article](https://betterexplained.com/articles/linear-algebra-guide/)
 * A Programmer's Intuition for Matrix Multiplication [Better Explained / Article](https://betterexplained.com/articles/matrix-multiplication/)
 * Vector Calculus: Understanding the Cross Product [Better Explained / Article](https://betterexplained.com/articles/cross-product/)
 * Vector Calculus: Understanding the Dot Product [Better Explained / Article](https://betterexplained.com/articles/vector-calculus-understanding-the-dot-product/)

#### **Convex Optimization**
 * Convex Optimization / Boyd [Stanford / Lectures](http://stanford.edu/class/ee364a/index.html) / [Book](http://stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf)

#### **Statistics**
 * Stats in a Nutshell [Book ```$29```](http://amzn.to/1iMnx2X)
 * Think Stats: Probability and Statistics for Programmers [Digital](http://bit.ly/ebook-thinkstats) & [Book ```$25```](http://amzn.to/RcVnTf)
 * Think Bayes [Digital](http://bit.ly/ebook-thinkbayes) & [Book ```$25```](http://amzn.to/1hmy4Cr)

#### **Differential Equations & Calculus**
 * Differential Equations in Data Science [Python Tutorial](http://bit.ly/ipynb-differentialeq)
#### **Problem Solving**
 * Problem-Solving Heuristics "How To Solve It" [Polya / Book ```$10```](http://amzn.to/1mqJRSi)
</details>
</summary>
### Computing

Get your environment up and running with the [Data Science Toolbox](http://bit.ly/datascitoolbox)

#### **Distributed Computing Paradigms**
 * *See Intro to Data Science [UW / Lectures on MapReduce](http://bit.ly/uwintrodatascience)
 * Intro to Hadoop and MapReduce [Cloudera / Udacity Course](http://bit.ly/udacity-hadoopmapreduce) *includes select free excerpts of Hadoop: The Definitive Guide [Book ```$29```](http://amzn.to/1i7wgLv)

#### **Databases**
 * Introduction to Databases [Stanford / Online Course](https://bit.ly/introdatabases)
 * SQL School [Mode Analytics / Tutorials](http://bit.ly/sqlschool)
 * SQL Tutorials [SQLZOO / Tutorials](http://bit.ly/tut-sqlzoo)

#### **Data Mining**
 * Mining Massive Data Sets / Stanford [Coursera](https://www.coursera.org/course/mmds) & [Digital](http://bit.ly/ebook-miningmassivedata) & [Book ```$58```](http://amzn.to/1txocpo)
 * Mining The Social Web [Book ```$30```](http://amzn.to/1mqxAsB)
 * Introduction to Information Retrieval / Stanford [Digital](http://bit.ly/ebook-stanford-inforetrieval) & [Book ```$56```](http://amzn.to/1mWbnUT)

#### **Data Design**
How does the real world get translated into data? How should one structure that data to make it understandable and usable? Extends beyond database design to usability of schemas and models.
 * [Tidy Data in Python](http://www.jeannicholashould.com/tidy-data-in-python.html)

_OSDSM Specialization: [Web Scraping & Crawling](https://github.com/datasciencemasters/go/blob/master/specializations.md#web-scraping--crawling)_

### **Machine Learning**

 _Foundational & Theoretical_
 * Machine Learning [Ng Stanford / Coursera](http://bit.ly/stanford-ml) & [Stanford CS 229](http://bit.ly/stanfordcs229)
 * A Course in Machine Learning [UMD / Digital Book](http://bit.ly/22WyV3N)
 * The Elements of Statistical Learning / Stanford [Digital](http://bit.ly/ebook-elemstatlearn) & [Book ```$80```](http://amzn.to/1hmyKry) & [Study Group](http://www.reddit.com/r/eosl)
 * Machine Learning [Caltech / Edx](http://bit.ly/caltech-ml)

 _Practical_
 * Programming Collective Intelligence [Book ```$27```](http://amzn.to/1mqxYqW)
 * Machine Learning for Hackers [ipynb / digital book](http://bit.ly/mlforhackers)
 * Intro to scikit-learn, SciPy2013 [youtube tutorials](http://bit.ly/scikit-video-tuts)

### **Probabilistic Modeling**
 * Probabilistic Programming and Bayesian Methods for Hackers [Github / Tutorials](http://bit.ly/ipnb-probabilisticprogramming)
 * Probabilistic Graphical Models [Stanford / Coursera](http://bit.ly/stanford-pgm)

#### **Deep Learning (Neural Networks)**
 * Neural Networks [Andrej Karpathy / Python Walkthrough](http://bit.ly/karpathyneuralnets)
 * Neural Networks [U Toronto / Coursera](http://bit.ly/utoronto-neuralnets)
 * Deep Learning for Natural Language Processing CS224d [Stanford](http://cs224d.stanford.edu/syllabus.html)

#### **Social Network & Graph Analysis**
 * Social and Economic Networks: Models and Analysis / [Stanford / Coursera](http://bit.ly/stanford-socialeconnetworks)
 * Social Network Analysis for Startups [Book ```$22```](http://amzn.to/1jySCCT)

#### **Natural Language Processing**
 * From Languages to Information / Stanford CS147 [Materials](http://bit.ly/nlpcs124)
 * NLP with Python (NLTK library) [Digital](http://bit.ly/ebook-nltk), [Book ```$36```](http://amzn.to/1iMrDIp)
 * How to Write a Spelling Correcter / Norvig (Tutorial)[http://norvig.com/spell-correct.html]

### Data Analysis
One of the "unteachable" skills of data science is an intuition for analysis. What constitutes valuable, achievable, and well-designed analysis is extremely dependent on context and ends at hand.

 * Big Data Analysis with Twitter [UC Berkeley / Lectures](http://bit.ly/cal-course-bigdatatwitter)
 * Exploratory Data Analysis [Tukey / Book ```$81```](http://amzn.to/1kNUEPa)

#### **in Python**
 * Data Analysis in Python [Tutorial](http://bit.ly/mode-python-tutorials)
 * Python for Data Analysis [Book ```$24```](http://amzn.to/Q2pI5I)
 * An Example Data Science Process [ipynb](http://bit.ly/ipydsprocess)

### Data Communication and Design

<summary>Data Visualization>
  <details>
  
 _Data Visualization and Communication_
 * The Truthful Art: Data, Charts, and Maps for Communication [Cairo / Book ```$21```](http://amzn.to/1UydGAc)

 _Theoretical Design of Information_

 * Envisioning Information [Tufte / Book ```$36```](http://amzn.to/Sn0QI4)
 * The Visual Display of Quantitative Information [Tufte / Book ```$27```](http://amzn.to/1q5FB91)

 _Applied Design of Information_
 * Information Dashboard Design: Displaying Data for At-a-Glance Monitoring [Stephen Few / Book ```$29```](http://amzn.to/1Vwz21v)

 _Theoretical Courses / Design & Visualization_

 * Data Visualization [University of Washington / Slides & Resources](http://bit.ly/uw-dataviz)
 * Berkeley's Viz Class [UC Berkeley / Course Docs](http://bit.ly/cal-viz)
 * Rice University's Data Viz class [Rice University / Slides](http://bit.ly/riceu-viz)

 _Practical Visualization Resources_

 * D3 Library / Scott Murray [Blog / Tutorials](http://bit.ly/tut-scottmurray-d3)
 * Interactive Data Visualization for the Web / Scott Murray [Online Book](http://bit.ly/interactive-data-viz-web) & [Book `$26`](http://amzn.to/1oK1xCN)
_OSDSM Specialization: [Data Journalism](https://github.com/datasciencemasters/go/blob/master/specializations.md#data-journalism)_

</details>
</summary>
<summary> Python Libraries, Packages, and APIs
  <details>
Installing Basic Packages [Python, virtualenv, NumPy, SciPy, matplotlib and IPython ](http://bit.ly/scientific-py-install) & [Using Python Scientifically](http://bit.ly/lecture-scipy)

[Command Line Install Script](https://github.com/fonnesbeck/ScipySuperpack) for Scientific Python Packages

 * [numpy Tutorial / Stanford CS231N](http://cs231n.github.io/python-numpy-tutorial/)
 * [Pandas Cookbook](http://bit.ly/jvnspandascookbook) (data structure library)

_More Libraries can be found in the ["awesome machine learning"](https://github.com/josephmisiti/awesome-machine-learning#python) repo & in related [specializations](https://github.com/datasciencemasters/go/blob/master/specializations.md)_

#### **Data Structures & Analysis Packages**
   * Flexible and powerful data analysis / manipulation library with labeled data structures objects, statistical functions, etc [pandas](http://bit.ly/py-pandas) & Tutorials [Python for Data Analysis / Book](http://amzn.to/Q2pI5I)

#### **Machine Learning Packages**
   * [scikit-learn](http://bit.ly/py-scikit) - Tools for Data Mining & Analysis

#### **Networks Packages**
   * [networkx](http://bit.ly/py-networkx) - Network Modeling & Viz

#### **Statistical Packages**
   * [PyMC](http://bit.ly/py-pymc) - Bayesian Inference & Markov Chain Monte Carlo sampling toolkit
   * [Statsmodels](http://bit.ly/py-statsmodel) - Python module that allows users to explore data, estimate statistical models, and perform statistical tests
   * [PyMVPA](http://bit.ly/py-mvpa) - Multivariate Pattern Analysis in Python

#### **Natural Language Processing & Understanding**
   * [NLTK](http://bit.ly/py-nltk) - Natural Language Toolkit
   * [Gensim](http://bit.ly/py-gensim) - Python library for topic modeling, document indexing and similarity retrieval with large corpora. Target audience is the natural language processing (NLP) and information retrieval (IR) community.

#### **Data APIs**
   * [twython](http://bit.ly/py-twython) - Python wrapper for the Twitter API

#### **Visualization Packages**
   * [matplotlib](http://bit.ly/matplotlib-docs) - well-integrated with analysis and data manipulation packages like numpy and pandas
   * [Seaborn](http://bit.ly/seaborn-python) - a high-level statistical visualization package built on top of matplotlib
</details>
</summary>

#### **iPython Data Science Notebooks**
 * [Data Science in IPython Notebooks](http://bit.ly/ipynb-ds) (Linear Regression, Logistic Regression, Random Forests, K-Means Clustering)
 * [A Gallery of Interesting IPython Notebooks - Pandas for Data Analysis](http://bit.ly/ipyfordataanalysis)

#### Datasets are now [here](http://bit.ly/osdsm-datasets-link)

#### R resources are now [here](http://bit.ly/osdsm-rresources)

### Data Science as a Profession

 * Doing Data Science: Straight Talk from the Frontline [O'Reilly / Book ```$25```](http://amzn.to/1vAIscK)
 * The Data Science Handbook: Advice and Insights from 25 Amazing Data Scientists [Book ```$22```](http://amzn.to/1J7lILJ)

### Capstone Project
* Capstone Analysis of Your Own Design; [Quora](http://bit.ly/quora-toyproblems)'s Idea Compendium
* Healthcare Twitter Analysis [Coursolve & UW Data Science](http://bit.ly/project-healthcare-twitter-analysis)
* Analyze your LinkedIn Network [Generate & Download Adjacency Matrix](http://socilab.com/)

***
### Resources

#### Read
* [DataTau](http://bit.ly/datatau) - The "Hacker News" of Data Science
* [Wikipedia](http://bit.ly/1kKg0gD) - The free encyclopedia
* [The Signal and The Noise - Nate Silver ```$15```](http://amzn.to/1hoxQoG) - Bestseller Pop Sci
* [Zipfian Academy's List of Resources](http://bit.ly/1qoF1We)
* [A Software Engineer's Guide to Getting Started with Data Science](http://bit.ly/1jwgV4p)
* [Data Scientist Interviews / Metamarkets](http://bit.ly/1r1tJot)
* [/r/MachineLearning](http://bit.ly/1uANaEM)

#### Watch & Listen
* [The Life of a Data Scientist / Josh Wills](https://www.youtube.com/watch?v=h9vQIPfe2uU)
* [The Talking Machines - Podcast about Machine Learning](http://www.thetalkingmachines.com/)
* [What Data Science Is / Hilary Mason](https://www.youtube.com/watch?v=fZuDwiM1XBQ)

#### Learn
* [Metacademy](http://bit.ly/metacademy) - Search for a concept you want to learn
* [Coursera](http://bit.ly/coursera-online-courses) - Online university courses
* [Wolfram Alpha](http://bit.ly/wolframalpha-torus) - The smart number and info cruncher
* [Khan Academy](http://bit.ly/khan-academy-lifeinsurance) - High quality, free learning videos

***

### Notation
Non-Open-Source books, courses, and resources are noted with ```$```.

## Contribute

Please Contribute -- **this is Open Source!**

[Follow me on Twitter @clarecorthell](http://bit.ly/clarecorthelltwitter)
