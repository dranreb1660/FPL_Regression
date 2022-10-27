## Description

FPL is an online fantasy game for the English Premier League. For the 2020/2021 season, the game is being played by approximately 8 million people (managers) across the world. The goal is to score as many points as possible from a select total of 15 players (11 starters + 4 substitutions) from the given pool of 687 players.

My hypothesis is that given the available player data every week, we can predict points scored for the coming week with enough accuracy, that we would personally use the model as a tool for player selection.

## Data

The data for this project was scrapped directly from the [official fantasy premier league website](https://fantasy.premierleague.com/statistics). Alternatively, the fantasy Premier League team provides an awesome API for the data but I chose the scrapping method for learning purposes

### Tools used for scraping

<em>> Selinum</em><br>
<em>> BeautifulSoup</em>

## Directory Structure

    .
    ├── AUTHORS.md
    ├── LICENSE
    ├── README.md
    ├── models  <- compiled model .pkl or HDFS or .pb format
    ├── config  <- any configuration files
    ├── data
    │   ├── interim <- data in intermediate processing stage
    │   ├── processed <- data after all preprocessing has been done
    │   └── raw <- original unmodified data acting as source of truth and provenance
    ├── docs  <- usage documentation or reference papers
    ├── notebooks <- jupyter notebooks for exploratory analysis and explanation
    ├── reports <- generated project artifacts eg. visualizations or tables
    │   └── figures
    └── src
        ├── data-proc <- scripts for processing data eg. transformations, dataset merges etc.
        ├── viz  <- scripts for visualization during EDA, modelling, error analysis etc.
        ├── modeling    <- scripts for generating models
    |--- requirements.txt <- file with libraries and library versions for recreating the analysis environment
