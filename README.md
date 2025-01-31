# Olympics-Dataset

This repo contains a comprehensive dataset on summer & winter Olympic athletes & their results between 1896-2022

# This project involves taking the raw data from [olympedia.org](https://www.olympedia.org/) and cleaning it up using Pandas to make it easier to analyze.

<img src="./assets/usain.jpg" width="600" alt="Usain Bolt">

## Dataset info & collection process

This data comes from [olympedia.org](https://www.olympedia.org/) and was web scraped with the Python Beautiful Soup library (see [scrape_data.py](./scrape_data.py))

- [athletes/bios.csv](./athletes/bios.csv) contains the raw biographical information on each athlete<br/>
- [results/results.csv](./results/results.csv) contains a row-by-row breakdown of each event athletes competed in and their results in that event.


## Clean Data

Easier to analyze data can be found in [clean-data/](./clean-data/) folder. In addition to the results and bios info, you can find data files with additional lat/long location data for athletes, NOC (National Olympic Committee) region codes, and historic populations of countries over time.
