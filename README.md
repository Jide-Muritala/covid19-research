# COVID-19 Research

The COVID-19 tourism impact research project analyzes the effects of the pandemic on the tourism industry through two main research threads:

1. Cruise Tourism: Investigates the impact of COVID-19 outbreaks on public perception of cruise tourism, particularly following the Diamond Princess incident, using Twitter data and Natural Language Processing (NLP).

2. Staycations: Examines the growth and practice of staycations during the pandemic using social media data, Latent Dirichlet Allocation (LDA) topic modeling, and Google Trends analytics.

## Publications
1. #CoronavirusCruise: Impact and implications of the COVID-19 outbreaks on the perception of cruise tourism ([Link](https://www.sciencedirect.com/science/article/pii/S2211973622000137))

2. COVID-19 staycations and the implications for leisure travel ([Link](https://www.cell.com/heliyon/fulltext/S2405-8440(22)02155-7))

## Research Objectives 

| Research Area     | Research Component        | Data Source    | Processing Methods                                              | Analysis Methods                     | Implementation File             | Expected Outcomes                                |
|-------------------|---------------------------|----------------|------------------------------------------------------------------|--------------------------------------|-------------------------------|--------------------------------------------------|
| Cruise Industry   | Cruise Industry Analysis  | Social Media   | Text preprocessing, Keyword detection                            | NLP sentiment analysis, Time series analysis | `cruise.ipynb`                | Understanding public perception, new business model recommendations |
| Cruise Industry   | Cruise Visualization      | Social Media   | Text preprocessing                                               | Keyword detection, Word cloud visualization | `cruise_ship_wordcloud.ipynb` | Crisis communication insights                   |
| Staycations       | Staycation Analysis       | Social Media   | Text cleaning, Tokenization, Stop word removal, Lemmatization    | LDA topic modeling, Topic coherence evaluation | `staycation.ipynb`           | Classification of 38 topics                      |
| Staycations       | Travel Behavior Analysis  | Google Trends  | Search interest extraction                                       | Google Trends analysis, Temporal pattern analysis | `staycation.ipynb`           | Behavioral change patterns                       |
| Staycations       | Psychological Distance    | Social Media   | Semantic embedding (implied)                                     | Semantic analysis                    | `staycation.ipynb`           | Understanding of proximity perception            |

## Methodology

![meth](https://github.com/user-attachments/assets/4d51fce8-0059-4fb1-89fa-c32a275a701e)

| Component           | Implementation                          | Function                                              |
|---------------------|------------------------------------------|-------------------------------------------------------|
| Text Preprocessing  | Regular expressions in `cruise.ipynb`    | Cleans and standardizes raw text data                |
| Sentiment Analysis  | NLTK's VADER in `cruise.ipynb`           | Quantifies sentiment in tweets                       |
| Keyword Detection   | `check_word_in_tweet()` function         | Identifies cruise-related content                    |
| Time Series Analysis| Pandas resampling in `cruise.ipynb`      | Aggregates data for temporal analysis                |
| Topic Modeling      | Latent Dirichlet Allocation              | Identifies thematic patterns in staycation data      |
| Visualization       | Matplotlib in `cruise.ipynb`             | Creates temporal and thematic visualizations         |

## Tech Stack

<p align="left">
<a href="https://jupyter.org/" target="_blank" rel="noreferrer"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" alt="jupyter" width="40" height="40"/> </a> 
&nbsp;
<a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> 
&nbsp;
<a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a>
&nbsp;
<a href="https://numpy.org/" target="_blank" rel="noreferrer"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" alt="numpy" width="40" height="40"/> </a> 
&nbsp;
<a href="https://matplotlib.org/" target="_blank" rel="noreferrer"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/matplotlib/matplotlib-original.svg" alt="matplotlib" width="40" height="40"/> </a> 
&nbsp;
<a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/scikitlearn/scikitlearn-original.svg" alt="scikit-learn" width="40" height="40" />  
&nbsp;
<a href="https://pytorch.org/" target="_blank" rel="noreferrer"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pytorch/pytorch-original.svg" alt="pytorch" width="40" height="40"/> </a>   
</p>

![stack](https://github.com/user-attachments/assets/0f58fd75-e624-47fa-8af8-5e98ce2cc4db)

| Library      | Purpose                                                                                      |
|--------------|----------------------------------------------------------------------------------------------|
| NLTK         | Natural language processing, stopwords, and sentiment analysis                              |
| Gensim       | Topic modeling implementation and text processing                                            |
| pyLDAvis     | Interactive visualization of topic models                                                    |
| Spacy        | Advanced NLP tasks like lemmatization                                                        |
| Pandas       | Data manipulation and analysis for both cruise and staycation datasets                      |
| NumPy        | Numerical operations                                                                         |
| Matplotlib   | Visualization of sentiment trends, topic modeling results, and temporal patterns            |
| re           | Regular expression pattern matching during text cleaning                                     |
| Torch        | Machine learning framework for NLP tasks, sentiment analysis, and topic modeling            |
| Torchvision  | Computer vision capabilities for processing image data                                       |
| ipywidgets   | Interactive components for Jupyter notebooks to allow dynamic analysis                       |
| tqdm         | Progress bars for monitoring long-running processes like data cleaning and model training   |

[.](https://deepwiki.com/Jide-Muritala/covid19-research)





