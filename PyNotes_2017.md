# PyNotes 2017

## Tel Aviv Meetup

**Fraud detection challenges and data skepticism using LIME** (_Shir Meir Lador_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=HcaAKI1tVGM
<br/>&nbsp;&nbsp;https://github.com/marcotcr/lime

- To view a random sample of dataframe: `df.sample(frac=1).head()`


## PyData London 2017

**Bayesian optimisation with scikit-learn** (_Thomas Huijskens_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=jtRPxRnOXnk

- Bayesian Optimization increases computational overhead, so only makes sense to use when the number of hyperparameters is very high, or it is computationally very expensive to evaluate the out of sample performance.
- GPs are the generalization of a Gaussian distribution to a distribution over _functions_, instead of random variables.
- Packages: Spearming, Hyperopt, MOE, Hyperband (model-free), SMAC (model-free)

**Ten Steps to Keras** (_Valerio Maggio_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=FrkYu2zVUyM
<br/>&nbsp;&nbsp;

**Bayesian Deep Learning with Edward (and a trick using Dropout)** (_Andrew Rowan_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=I09QVNrUS3Q


**Next generation of word embeddings in Gensim** (_Lev Konstantinovskiy_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=7530Tn2J0Mc


**Dimension Reduction and Extracting Topics - A Gentle Introduction** (_Tariq Rashid_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=Bxlzbck51SU
<br/>&nbsp;&nbsp;http://makeyourowntextminingtoolkit.blogspot.co.uk/


**Make your research interactive with Jupyter Dashboards** (_Pavlo Andriychenko_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=qQaBv7gw8vw


## Add the previous videos for this conference (e.g., Using RFs.)



## PyCon 2017

**Kubernetes for Pythonistas** (_Kelsey Hightower_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=u_iAXzy3xBA

- (Really fun Tetris example of scheduling)

**Probabilistic Programming with PyMC3** (_Christopher Fonnesbeck_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=5TyvJ6jXHYE

**The Python Visualization Landscape** (_Jake VanderPlas_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=FytuB8nFHPQ

**Optimizing Pandas Code for Speed and Efficiency** (_Sofia Heisler_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=HN5d490_KKk

**Keynote** (_Jake Vanderplas_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=ZyjCqQEUa8o

**The Fastest FizzBuzz in the West** (_Dustin Ingram_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=ApgUrtCrmV8

```python
def fizzbuzz(n):
  for i in range(n):
    print(i%3//2*'fizz'+i%5//4*'buzz' or i+1)
```

**An Introduction to Reinforcement Learning** (_Jessica Forde_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=k1UuTyW2uFc

**Human Machine Collaboration for Improved Analytical Processes** (_Tony Ojeda_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=s0u_UkVecx0

**The Dictionary Even Mightier** (_Brandon Rhodes_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=66P5FMkWoVU

**Modern Python Dictionaries -- A confluence of a dozen great ideas** (_Raymond Hettinger_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=npw4s1QTmPg

**What's new in Python 3.6** (_Brett Cannon_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=c2rEbbGLPQc

**Readability Counts** (_Trey Hunner_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=knMg6G9_XCg

**The Wild West of Data Wrangling** (_Sarah Guido_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=xn9sTXR3Cp8

**Dask: A Pythonic Distributed Data Science Framework** (_Matthew Rocklin_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=RA_2qdipVng

**Factory Automation with Python Stories about Robots, Serial Ports, and Barcode Readers** (_Jonas Neubert_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=cEyVfiix1Lw

**Snakes on a Hyperplane Python Machine Learning in Production** (_Jessica Lundin_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=oV-cm0Loefg

**A gentle introduction to deep learning with TensorFlow** (_Michelle Fullwood_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=5e0TbyCkbCY

**Looping Like a Pro in Python** (_David DB Baumgold_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=u8g9scXeAcI

**Instagram Filters in 15 Lines of Python** (_Michele Pratusevich_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=otLGDpBglEA

**Passing Exceptions 101 Paradigms in Error Handling** (_Amandine Lee_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=BMtJbrvwlmo

**Python Epiphanies [Tutorial]** (_Stuart Williams_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=oQca6eDcjA8

**Intro to Bayesian Machine Learning with PyMC3 and Edward [Tutorial]** (_Torsten Scholak, Diego Maniloff_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=fR5Wvb86-IU
<br/>&nbsp;&nbsp;http://tscholak.github.io/assets/PyConEdward/#/

**Parallel Data Analysis [Tutorial]** (_Ben Zaitlen, Matthew Rocklin, Min Ragan Kelley, Olivier Grisel_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=KIXACCJHtDg

**Build a data pipeline with Luigi [Tutorial]** (_Aaron Knight_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=jpkZGXrhZJ8

**Faster Python Programs Measure, don't Guess [Tutorial]** (_Mike Müller_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=xmuEsYut9Pc

**Python and Jupyter in Depth: High productivity, interactive Python [Tutorial]** (_Matthias Bussonnier, Mike Bright, Min Ragan-Kelley_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=VQBZ2MqWBZI

**Introduction to Digital Signal Processing [Tutorial]** (_Allen Downey_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=UOIllEyajGs

**Deploy and scale containers with Docker native, open source orchestration [Tutorial]** (_Jerome Petazzoni, AJ Bowen_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=EuzoEaE6Cqs

**Hands On Intro to Python for New Programmers [Tutorial]** (_Trey Hunner_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=6zu8lrYn6t8

**Time Series Analysis** (_Aileen Nielsen_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=zmfe2RaX-14

**Decorators and descriptors decoded** (_Luciano Ramalho_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=81S01c9zytE

**Fantastic Data and Where To Find Them: An introduction to APIs, RSS, and Scraping** (_Nicole Donnelly, Tony Ojeda, Will Voorhees_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=A42voDYkFZw

**Introduction to Statistical Modeling with Python** (_Christopher Fonnesbeck_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=TMmSESkhRtI

**bokeh: Data Visualization in Python** (_Chalmer Lowe_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=xId9B1BVusA

**Exploratory data analysis in pytho** (_Chloe Mawer, Jonathan Whitmore_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=W5WE9Db2RLU
<br/>&nbsp;&nbsp;https://github.com/cmawer/pycon-2017-eda-tutorial/

**Using Functional Programming for efficient Data Processing and Analysis** (_Reuben Cummings_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=9kDUTJahXBM
<br/>&nbsp;&nbsp;https://speakerdeck.com/reubano/using-functional-programming-for-efficient-data-processing-and-analysis
<br/>&nbsp;&nbsp;https://github.com/reubano/pycon17-tute


## PyData London

**SaaaS - Sampling as an Algorithm Service** (_Vincent D. Warmerdam_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=8g6oF8vUqTU
<br/>&nbsp;&nbsp;http://koaning.io/switching-to-sampling-in-order-to-switch.html
<br/>&nbsp;&nbsp;http://koaning.io/elimination-via-inference.html

- _(Approachable introduction to MCMC)_ 
- Uses the Kaggle [Santa's Uncertain Bags Competition](https://www.kaggle.com/c/santas-uncertain-bags) as an example


## Misc

**Use Python to Load & Prepare Data Analytics** (_Raymond Hettinger _)
<br/>https://www.youtube.com/watch?v=nO78ECRighw

```python
from collections import defaultdict
from pprint import pprint

d = defaultdict(list)
d['a'].append('apple')
d = dict(d) # to convert to regular dict
pprint(d)

# start @ 11:52

```





## ...

**xxx** (_xxx_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;


