# Throw Ins: Gain the Upper Hand
<!-- PROJECT LOGO -->
<br />
<div align="center">
  </a>
  <h3 align="center">Throw Ins: Gain the Upper Hand</h3>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li><a href="#usage">Usage</a></li>
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
