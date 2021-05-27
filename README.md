# LearningML-Projects
A collection of projects I first took on and experimented with when I began learning Data Science, Machine Learning (ML), and Deep Learning (DL).

[![Made with Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-F3f0f0?&logo=Jupyter&labelColor=F3f0f0)](https://jupyter.org/try)
[![Python](https://img.shields.io/badge/Python-3.8.3-21455f?logo=python&labelColor=21455f)](https://www.python.org/)
[![Joblib](https://img.shields.io/badge/Joblib-0.17.0-21455f?labelColor=21455f)](https://joblib.readthedocs.io/en/latest/)
[![PIL](https://img.shields.io/badge/PIL-7.2.0-21455f?labelColor=21455f)](https://pillow.readthedocs.io/en/stable/)
[![NumPy](https://img.shields.io/badge/NumPy-1.19.5-013243?logo=numpy&labelColor=013243)](https://numpy.org/doc/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.3.2-085678?labelColor=085678)](https://matplotlib.org/)
[![Pandas](https://img.shields.io/badge/Pandas-1.2.4-150458?logo=pandas&labelColor=150458)](https://pandas.pydata.org/pandas-docs/stable/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-3.3.2-319ace?logo=scikit-learn&labelColor=319ace)](https://scikit-learn.org/stable/index.html)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.4.1-F3f0f0?logo=tensorflow&labelColor=F3f0f0)](https://www.tensorflow.org/api_docs/)
[![Keras Tuner](https://img.shields.io/badge/Keras%20Tuner-1.0.2-D00000?logo=keras&labelColor=D00000)](https://keras-team.github.io/keras-tuner/)
[![OpenAI-Gym](https://img.shields.io/badge/OpenAI--Gym-0.18.0-0081A5?logo=OpenAI%20Gym&labelColor=0081A5)](https://gym.openai.com/)
[![TF-Agents](https://img.shields.io/badge/TF-Agents-0.7.1-F3f0f0?logo=tensorflow&labelColor=F3f0f0)](https://www.tensorflow.org/agents)
[![Gmail 1](https://img.shields.io/badge/Gmail-tuvincent0106%40gmail.com-F3f0f0?logo=gmail&labelColor=F3f0f0)](https://mail.google.com/mail/?view=cm&fs=1&to=tuvincent0106@gmail.com)
[![Gmail 2](https://img.shields.io/badge/Gmail-alckasoc%40gmail.com-F3f0f0?logo=gmail&labelColor=F3f0f0)](https://mail.google.com/mail/?view=cm&fs=1&to=tuvincent0106@gmail.com)
[![Linkedin](https://img.shields.io/badge/Linkedin-Vincent%20Tu-0A66C2?logo=linkedin&labelColor=0A66C2)](https://www.linkedin.com/in/vincent-tu-422b18208)
[![Discord](https://img.shields.io/badge/Discord-alckasoc%235261-7187da?logo=discord&labelColor=7288db&logoColor=white)](https://discordapp.com/users/251152357063131138/)
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg?labelColor=blue)](https://raw.githubusercontent.com/alckasoc/LearningML-Projects/main/LICENSE)

## Table of Contents:
- [Motivation](https://github.com/alckasoc/LearningML-Projects/blob/main/README.md#motivation)
- [Technologies](https://github.com/alckasoc/Joblisting-Webscraper/blob/main/README.md#technologies)
- [Requirements for Use](https://github.com/alckasoc/Joblisting-Webscraper/blob/main/README.md#requirements-for-use)
- [Author Info](https://github.com/alckasoc/Joblisting-Webscraper/blob/main/README.md#author-info)
- [Future Notice](https://github.com/alckasoc/Joblisting-Webscraper/blob/main/README.md#future-notice)

## Motivation

Inspired by Omer Sakarya's [glassdoor-webscraper-selenium](https://github.com/arapfaik/scraping-glassdoor-selenium) project and aiming to create a data science project from end to end, I took the opportunity to explore the webscraping world and create a project. I found webscraping joblistings from Glassdoor.com to be valuable for a wealth of applications: quickly generating real-life applicable data, the generated data can be wrangled with and explored through exploratory data analysis (EDA). Additionally, it could have the potential of helping future employers and job seekers discover demographics previously hidden (I hope).

## Technologies

re:

I used RegEx for parsing and searching strings. This was helpful for reading in different filter options and scraping data.

time:

Time was for a time.sleep() delay —since internet speed can affect how quickly a page loads and Glassdoor.com has a slightly slow page load up. Successive calls to functions can also be skipped over if the page does not load fast enough.

selenium:

I used selenium for this project because it, unlike beautifulsoup4, allows for JavaScript which proved especially helpful in one of the large difficulties of this project.

pandas:

I used pandas for creating the dataframe after the job webscraping is done.

## Requirements for Use

- I used Google Chrome Version 90.0.4430.212 and its corresponding Chromedriver for this project (you can find your Chromedriver [here](https://sites.google.com/a/chromium.org/chromedriver/downloads)). To check Chrome version, navigate to a Google browser and click the upper right three dots > Settings > Help > About Google Chrome.
- Python ≥ 3.8.3.
- Selenium ≥ 3.141.0.
- Pandas ≥ 1.2.4.

## Author Info

Contact me:

Gmail: tuvincent0106@gmail.com (preferably) or alckasoc@gmail.com\
Linkedin (I have not configured my Linkedin profile yet!): [Vincent Tu](https://www.linkedin.com/in/vincent-tu-422b18208/)\
Discord: [alckasoc#5261](https://discordapp.com/users/251152357063131138/)

## Future Notice

As of now, this project works. However, as joblistings are constantly updated, and consequently Glassdoor.com's joblistings and jobpage will consistently update (also general website updates), there may be a time where this project may not work as intended. I never expected this project to reach this size. With more documentation, docstrings, comments, and functions, I found the project's line of code size growing rapidly. Downloading this project is definitely a hassle as it is not a PyPI package. However, my choice to not make it a PyPI package is because I do not plan on maintaining this project with the oncoming future updates to Glassdoor.com. However, regardless of where this project stands, I can say that it has been a priceless journey. I've learned a wealth of material and topics not to mention the joy I've experienced in seeing my huge block of code run without errors. 

