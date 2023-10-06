# dim-red-inquirer
This data mining project employs dimensionality reduction techniques to generate clusters for documents.

![Header](header.png)

## Overview

In this study, we aimed to analyze the prevalent topics and issues covered by the top news media outlet in the Philippines, Inquirer, during the administration of former President Rodrigo Duterte. Our goal was to shed light on critical social topics that may have significantly impacted the lives of Filipinos and to assess news bias or partiality in the reporting. By identifying and highlighting these important social issues, we aimed to create awareness among public officials, society, concerned groups, and experts, which could lead to better public policy initiatives and support from various stakeholders. `metro_scrape.ipynb` contains the technical report for the project.

## Dataset

We gathered our data by scraping news articles from the [Inquirer website](https://www.inquirer.net), specifically focusing on the Metro News section from June 30, 2016, to June 30, 2022. This dataset comprises a total of 6,961 news articles, with an average length of about 340 words per article. This process is documented in `metro_inquirer_web_scrape.ipynb`.

## Key Highlights

The analysis revealed the following insights:

- The most prominent news topic during the initial years of Duterte's presidency (2016-2017) was the "Drug War," aligning with one of Duterte's major campaign promises to combat drug-related issues in the Philippines.

- In the subsequent years (2018-2019), "Politics" emerged as a popular news topic, briefly interrupted by a surge in COVID-19-related news in 2020, coinciding with the global pandemic. 

- Politics-related news returned as the dominant topic in 2021, marking the start of the elections campaign.

- Throughout Duterte's six-year term, topics such as "Traffic Incidents," "Transportation," and "Fire Incidents" consistently garnered attention, signifying social concerns deserving further investigation by leaders.

## Installation
To replicate our analysis, you can install the required Python libraries by running the following command:
```bash
pip install -r requirements.txt
```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.