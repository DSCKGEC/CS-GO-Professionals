
# CS-GO-Professionals


[![Contributors](https://img.shields.io/github/contributors/dsckgec/CS-GO-Professionals.svg)](https://github.com/dsckgec/CS-GO-Professionals/graphs/contributors) [![Forks](https://img.shields.io/github/forks/dsckgec/CS-GO-Professionals.svg)](https://github.com/dsckgec/CS-GO-Professionals/network/members) [![Issues](https://img.shields.io/github/issues/dsckgec/CS-GO-Professionals.svg)](https://github.com/dsckgec/CS-GO-Professionals/issues) [![Pull Request](https://img.shields.io/github/issues-pr-closed-raw/dsckgec/CS-GO-Professionals)](https://github.com/dsckgec/CS-GO-Professionals/pulls)


![CSGO](https://cdn.akamai.steamstatic.com/steam/apps/730/ss_60b4f959497899515f46012df805b0006ef21af6.1920x1080.jpg?t=1641233427)


## Contents

1. [Description](#description)
1. [Project structure](#project-structure)
1. [Getting started](#getting-started)
1. [Contributing](#contributing)
1. [Authors](#authors)
1. [License](#license)


## Description

Counter-Strike: Global Offensive is a 2012 multiplayer first-person shooter developed by Valve and Hidden Path Entertainment. It is the fourth game in the Counter-Strike series.
It is one of the biggest eSports title out there. In this project we scrape and work on a dataset of all CSGO Athletes.

The entire flow of the project includes:
- Scrape the Dataset from this [Website](https://www.hltv.org/stats/players)
- Perform Feature Engineering to create insightful columns
- Perform Exploratory Data Analysis to create insights and meaningful dashboards

## Project structure

```   
  ├── scraping notebook.ipynb             Notebook for Scraping the website
  ├── feature engineering.ipynb           Notebook for deriving new features from Raw data 
  ├── CSGO Player Dataset(Raw).csv        Original Dataset about CSGO Player Dataset
  ├── CSGO Player Dataset(FE).csv         Dataset with added features 'Kills' and 'Deaths' about CSGO Player Dataset
```
## Getting started


### Prerequisites

#### Software Needed
 
  1. A web browser. 

         OR
         
  3. Anaconda software.

#### Knowledge Needed
- Very basic understanding of git and github:

    1.  What are repositories (local - remote - upstream), issues, pull requests
    2.   How to clone a repository, how to fork a repository, how to set upstreams
    3.   Adding, committing, pulling, pushing changes to remote repositories

- For EDA and Visualisation
 
    1. Basic syntax and working of ```python```.(This is a must)
    2. Basic knowledge of ```pandas``` library. [Reading this blog might help.](https://www.dataquest.io/blog/pandas-python-tutorial/)
    3. Basic knowledge of ```matplotlib``` library. [Reading this blog might help.](https://blog.quantinsti.com/python-matplotlib-tutorial/)
    4. Basic knowledge of ```seaborn``` library. [Reading this blog might help.](https://www.mygreatlearning.com/blog/seaborn-tutorial/)
    5. Basic knowledge of ```scikit learn``` library. [Reading this blog might help.](https://www.dataquest.io/blog/sci-kit-learn-tutorial/)

  However the code is well explained, so anyone knowing the basics of Python can get a idea of what's happenning and contribute to this.

### Installing

Clone the project

```bash
  git clone https://github.com/DSCKGEC/CS-GO-Professionals.git
```

Go to the project directory

```bash
  cd CS-GO-Professionals
```

To run this:
```bash
  pip install bs4
  pip install pandas
  pip install requests
```


## Contributing

Please read [contributing.md](contributing.md) for details on our code of conduct, and the process for submitting pull requests to us.


## Authors

- [@sbk2k1](https://github.com/sbk2k1)
- [@AryaChakraborty](https://github.com/AryaChakraborty)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
