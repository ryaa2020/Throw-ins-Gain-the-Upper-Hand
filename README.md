# Throw Ins: Gain the Upper Hand

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## About The Project

Throw-ins: the one time players are able to hold the ball. Our goal in this project is to analyze the success of throw-ins during soccer matches using throw-in location and other factors such as pass length, pass height, pass angle, and which player throws the ball in. There is a general lack of research on throw-in plays. While throw-ins are generally considered to be the least important set piece, we view them as a valuable, frequent occurrence – pretty much the only one that allows players to pause gameplay and pick up the ball. 

## Getting Started

### Prerequisites

![Python Badge](https://img.shields.io/badge/-python-3f7dae?style=flat&logo=python&logoColor=fff)
[![Jupyter Badge](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=flat&logo=Jupyter)](https://jupyter.org/try)

<!--This project is written in Python programming language. <br>-->
To use this GitHub repo, you need a computer and internet connection.

The following open-source [Python](https://www.python.org/) libraries listed below are the ones that feature in the the notebooks in this repository. Most of these libraries can be obtained by downloading and installing [Anaconda](https://anaconda.org/anaconda/conda). Step-by-step guides to do this can be found for Windows [here](https://medium.com/@GalarnykMichael/install-python-on-windows-anaconda-c63c7c3d1444) and Mac [here](https://medium.com/@GalarnykMichael/install-python-on-mac-anaconda-ccd9f2014072), as well as in the Anaconda documentation itself [here](https://docs.anaconda.com/anaconda/install/).

*    [NumPy](https://numpy.org/doc/stable/contents.html);
*    [pandas](http://pandas.pydata.org/);
*    [matplotlib](https://matplotlib.org/contents.html?v=20200411155018);
*    [scikit-learn](https://scikit-learn.org/stable/);
*    [statsmodel](https://www.statsmodels.org/stable/index.html);
*    [statsbombpy](https://github.com/statsbomb/statsbombpy);
*    [json](https://docs.python.org/3/library/json.html);
*    [mplsoccer](https://mplsoccer.readthedocs.io/en/latest/index.html);
*    [seaborn](https://seaborn.pydata.org/);
*    [os](https://docs.python.org/3/library/os.html);
*    [re](https://docs.python.org/3/library/re.html); and
*    [prettytable](https://pypi.org/project/prettytable/).


### Installation

You will need to install the libraries listed above to run our code. You can find instructions on how to do so [here](https://docs.python.org/3/installing/index.html).

This is an example of how to get Statsbomb event data. 
* Statsbomb
  ```sh
  sb.events(match_id = 3788741)
  ```

<p align="right"><a href="#table-of-contents">Back to Contents</a>


## Usage

This project can be used to analyze soccer throw-ins and provide soccer teams with data on how to more successfully utilize their throw-in opportunities.
More specifically... 
  + Defensively, teams can strategize when clearing the ball out of play – they may be able to control what section of the sideline they kick it out at, allowing them to direct the throw-in to areas of lower success for the throw-in team. 
  + Offensively, our work demonstrates some of the strategies for throwing the ball in successfully when it comes to variables like angle and distance, as well as giving data on which players are best at performing throw-ins. Moreover, teams can adjust their throw-in set pieces, leading to more scoring opportunities. 
  + Coaching staff can also analyze the throw-ins of players on other teams who often throw the ball in and use our data to predict their tendencies, such as throwing in the ball low or high, in order to best defend against their throw-in. Our data can also help determine which players are best at throw-ins and others who may need some practice. 


<p align="right"><a href="#table-of-contents">Back to Contents</a>

## Navigating our Code

The project is organized into several folders. 
  + The starter.ipynb and regression.ipynb are files we used to experiment. 
  + The fullData folder contains the code we used to access all the necessary data and create files to store that data. 
    + getFullData.ipynb
    + fulldata.csv
    + full_data_sorted.csv
  + The firstContact folder contains all of our files relevant to making successful first contact after a throw-in.
    + analyze_throwIn.ipynb
    + firstContact.ipynb
    + firstContact_regression.ipynb
  + The playerThrowIn folder holds all of our work relating to player-specific throw-in data. 
    + player_throwIn.ipynb
  + The retainPossession folder contains our work on determining whether a team retains possession of the ball after a throw-in. 
    + retainPossession.ipynb
  + The shotOnGoal folder contains unfinished files that investigate shot creation in relation to throw-ins. 
    + shot_on_goal.ipynb
    + shot_regression.ipynb

<p align="right"><a href="#table-of-contents">Back to Contents</a>

## Contact

Anna: aeha2020@mymail.pomona.edu

Rachel: ryaa2020@mymail.pomona.edu

Project Link: https://github.com/ryaa2020/Throw-ins-Gain-the-Upper-Hand/

<p align="right"><a href="#table-of-contents">Back to Contents</a>

## Acknowledgments

Thank you to Women in Sports Data for providing this opportunity for us to research this topic. We also want to thank our mentor, LJ Rader, for helping us throughout our process. Lastly, we want to thank StatsBomb for the ample amount of data they provided us with to do our research! 

<p align="right"><a href="#table-of-contents">Back to Contents</a>
