[![Python 3.7](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-360/)   

![header](https://capsule-render.vercel.app/api?type=wave&color=gradient&height=300&section=header&text=Bibble%20App&fontSize=90)

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)  


# BIBLE APP WITH NLP ANALYSIS




## ✅ Goal
To create an Application that tracks Covid cases in different Countries

## ✅ Tech stack!
    * Python
    * Heroku
    * altair
    * textblob
    * pandas
    * matplotlib
    * streamlit
    * neattext
    * spacy>
    
<code><img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" title="python"></code>
<code><img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/heroku/heroku-original.svg" title="heroku"></code>
<code><img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" title="git"></code>



## ✅ MOTIVATION


## ✅ What does it do? 

## ✅ Features
1. Single Verse Search -
2. Multiverse Verse Search
3. Random Verse of the day
4. Term/Topic in the bible
5. Part Of Speech tag- Detect whether it is a Noun, Verb, Adjective, etc
indicated with different color
6. Where color Green is a Noun, Blue is a verb, etc
7. Main keyword in bible verse
8. Part Of Speech Tag Plot - Plots for the Part of Speech(Histogram).
9. Word Frequency Plot- Number of words in that verse(Histogram).


## 🙋‍♀️ Authors

<p align='center'>
<a href="mailto:giftoscart@gmail.com">
  <img src="https://img.shields.io/badge/email-%23D14836.svg?&style=for-the-badge&logo=gmail&logoColor=white" />
</a>&nbsp;&nbsp;
  <a href="https://www.linkedin.com/posts/gift-ojabu_webappdevelopment-pythonprogramming-streamlit-activity-6764841612100046849-0Ok3">
  <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />
</a>&nbsp;&nbsp;


# What I Learned
<ul>
    <li> Using react and fetch calls to dynamically update UI.</li>
    <li> Reinforced knowledge of API integration. </li>
    <li> Leaflet.js / Chart.js libraries were used to create the interactive map and  
    responsive line graph components </li>
    <li> CSS and Material-UI libraries were used to design animations and web layout. </li>
</ul>




## Introduction

This Python Projects is created with Streamlit and hosted on Heroku 
## Get Started

- Download [Python 3](https://python.org/downloads)
- Pip install streamlit

## Usage

Streamlit is A python framework for buiding data apllication.













# streamlit-bible-app
I built a bible app with streamlit deployed on heroku that has features like part of speech bible text tag, counts of word and graphs of word count.

```python
# A function to read our dataset-An Headstart
@st.cache
def load_bible(data):
    df = pd.read_csv(data)
    return df
    
    def main():
    stc.html(HTML_BANNER)
    menu = ["Home", "MultiVerse", "About"]

    df = load_bible("data/KJV_Bible.csv")
```

## 🚀 Quick Start

1. Install all the packages:
    ```bash
    pip install requirements.txt
    ```
2. Run the demo:
    ```bash
    streamlit run app.py
    ```
3. View the Streamlit app in your browser: `http://localhost:8501`
