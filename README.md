# Throw Ins: Gain the Upper Hand

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li><a href="#built with">Built With</a></li>
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

## Built With

## Getting Started

### Prerequisites

![Python Badge](https://img.shields.io/badge/-python-3f7dae?style=flat&logo=python&logoColor=fff)
[![Jupyter Badge](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=flat&logo=Jupyter)](https://jupyter.org/try)

<!--This project is written in Python programming language. <br>-->
The only prerequisites for using this GitHub repo is that you have a computer, internet connection and the desire to learn more about football analytics. 

The following open-source [Python](https://www.python.org/) libraries listed below are some of the most commonly used in Data Science that feature in the the notebooks in this repository. Most of these libraries can be obtained by downloading and installing [Anaconda](https://anaconda.org/anaconda/conda). Step-by-step guides to do this can be found for Windows [here](https://medium.com/@GalarnykMichael/install-python-on-windows-anaconda-c63c7c3d1444) and Mac [here](https://medium.com/@GalarnykMichael/install-python-on-mac-anaconda-ccd9f2014072), as well as in the Anaconda documentation itself [here](https://docs.anaconda.com/anaconda/install/).

*    [NumPy](https://numpy.org/doc/stable/contents.html);
*    [pandas](http://pandas.pydata.org/);
*    [matplotlib](https://matplotlib.org/contents.html?v=20200411155018);
*    [Plotly](https://plotly.com/);
*    [record linkage](https://recordlinkage.readthedocs.io/en/latest/about.html);
*    [scikit-learn](https://scikit-learn.org/stable/);
*    [SciPy](https://www.scipy.org/);
*    [XGBoost](https://xgboost.readthedocs.io/en/latest/);
*    [Hyperopt](https://github.com/hyperopt/hyperopt);
*    [MLflow](https://github.com/mlflow/mlflow); 
*    [SHAP](https://github.com/slundberg/shap);
*    [statsbombpy](https://github.com/statsbomb/statsbombpy);
*    [json](https://docs.python.org/3/library/json.html);
*    [mplsoccer](https://mplsoccer.readthedocs.io/en/latest/index.html);
*    [seaborn](https://seaborn.pydata.org/);
*    [os](https://docs.python.org/3/library/os.html);
*    [re](https://docs.python.org/3/library/re.html); and
*    [prettytable](https://pypi.org/project/prettytable/).

<a href="#table-of-contents">Back to Contents</a>


### Installation

## Usage

## Roadmap

## Contributing

## Contact

## Acknowledgments


# StatsBomb Open Data

Welcome to the StatsBomb Open Data repository.

StatsBomb are committed to sharing new data and research publicly to enhance understanding of the game of Football. We want to actively encourage new research and analysis at all levels. Therefore we have made certain leagues of StatsBomb Data freely available for public use for research projects and genuine interest in football analytics.

StatsBomb are hoping that by making data freely available, we will extend the wider football analytics community and attract new talent to the industry.

## Terms & Conditions

If you publish, share or distribute any research, analysis or insights based on this data, please state the data source as StatsBomb and use our logo, available in our [Media Pack](https://statsbomb.com/media-pack/).

## Getting Started

The [data](./data/) is provided as JSON files exported from the StatsBomb Data API, in the following structure:

* Competition and seasons stored in [`competitions.json`](./data/competitions.json).
* Matches for each competition and season, stored in [`matches`](./data/matches/). Each folder within is named for a competition ID, each file is named for a season ID within that competition.
* Events and lineups for each match, stored in [`events`](./data/events/) and [`lineups`](./data/lineups/) respectively. Each file is named for a match ID.
* StatsBomb 360 data for selected matches, stored in [`three-sixty`](./data/three-sixty/). Each file is named for a match ID.

Some documentation about the meaning of different events and the format of the JSON can be found in the [`doc`](./doc) directory.
