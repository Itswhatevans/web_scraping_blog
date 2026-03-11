# Web Scraping Blog
Here I will develop an API web scraper to assemble a dataset for a tutorial blog post which I'll host on my GitHub pages site!
Follow along with me as I interface with a public API, gather a data set, and give you general steps to help you kickstart your web scraping journey!

This repo will contain the efforts I make toward scraping rocket launch data gathered from the Space Launch Now API
I'll use Python code to develop/implement the API, store data as a .csv file, and perform data analysis tasks with it.

This project builds an original dataset of rocket launches by collecting data from public aerospace APIs and web sources. The goal is to curate a structured dataset containing launch providers, vehicles, launch sites, and mission details for analysis of trends in modern spaceflight.

The dataset is created using Python with API requests and web scraping tools such as requests and BeautifulSoup.

## Research Question

How has global rocket launch activity changed in recent years, and which providers and launch sites account for most launches?

## Data Sources

Launch data is collected from:

- :contentReference[oaicite:0]{index=0} Launch Library API
- :contentReference[oaicite:1]{index=1} launch history tables

These sources provide information about launch vehicles, launch providers, missions, and launch sites.


## Repository Structure

rocket-launch-dataset/
│
├── scraper.ipynb        # notebook used to collect data
├── data/
│   ├── raw/             # raw API responses
│   └── cleaned/         # final dataset
├── analysis/            # exploratory analysis notebooks
└── README.md

## Technologies

- Python
- requests
- BeautifulSoup
- pandas

## Running the Scraper

1. Clone the repository
2. Open `scraper.ipynb`
3. Run the cells to retrieve launch data from the API
4. The dataset will be saved to `/data/cleaned/`