# DATASCI 266: Final Project

## Headline Evaluation and Style Independency in Journalism
####  Rafael Arbex-Murut, Yeshwanth Somu

The intention of this project is to quantify predictability in journalism. We accomplished this by analyzing the relationships between the headlines of articles, the bodies of articles, and their respective editorial sources. We measured the propensity of news outlets to have descriptive headlines for their own articles, and on the same dataset, we also measured the uniqueness of news sources’ editorial styles.

## Data 

We used the [*All the News*](https://www.kaggle.com/datasets/snapcrack/all-the-news) dataset, which can be downloaded from Kaggle.  This dataset includes over 140,000 news articles from 15 different American publications. The dataset was built from RSS feeds, thus capturing the most prominent articles of each publication.

## Repo Structure

Our project is structured into two subdirectories covering both portions of the project. A final report and presentation are included in the main directory.

```bash
├── Final Report.pdf
├── Headline Evaluation                                              #Headline evaluation using T5 and Pegasus. Algorithm and results included as png files
│   ├── Determining Pegasus Parameters.ipynb
│   ├── Determining T5 Parameters.ipynb
│   ├── Evaluation Headlines Pegasus.ipynb
│   ├── Evaluation Headlines T5.ipynb
│   ├── Headline Evaluation Algorithm.png
│   ├── Pegasus RougeL Scores.png
│   ├── T5 RougeL Scores.png
│   └── Visuals Headline Evaluation.ipynb
├── News Outlet Classification                                      #Classification done on full set of 12 news putlets, and subset of 6 news outlets
│   ├── Full Classification.ipynb
│   ├── Outlet Classification Confusion Matrix - 12 Outlets.png
│   ├── Outlet Classification Confusion Matrix - 6 Outlets.png
│   └── Subset Classification.ipynb
├── Presentation.pdf
└── README.md
```
