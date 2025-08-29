# Nobel Prize Data Analysis (1901–2023)

![Nobel Prize](Nobel_Prize.png)

This project analyzes the Nobel Prize dataset, which contains information about all laureates from the inception of the awards in 1901 up to 2023. The dataset is sourced from the **Nobel Prize API** and is included as `nobel.csv` in the `data` folder.

## Overview

The Nobel Prize is one of the most prestigious international awards. Each year, prizes are awarded in the following categories:

- Chemistry
- Literature
- Physics
- Physiology or Medicine
- Economics
- Peace

Along with the honor, prestige, and substantial prize money, each recipient receives a gold medal featuring an image of Alfred Nobel (1833–1896), who established the prize.

## Questions Explored in This Project

1. **Most Common Gender and Birth Country**  
   Identify the gender and birth country most frequently awarded a Nobel Prize.

2. **Decade with Highest Ratio of US-born Laureates**  
   Determine which decade had the highest proportion of US-born Nobel Prize winners relative to the total winners in all categories.

3. **Decade and Category with Highest Female Proportion**  
   Find the combination of decade and Nobel Prize category with the highest proportion of female laureates.

4. **First Woman to Receive a Nobel Prize**  
   Identify who the first female laureate was and the category she won in.

5. **Multiple-Time Nobel Laureates**  
   List individuals or organizations who have won more than one Nobel Prize over the years.

## Dataset

- **File:** `data/nobel.csv`  
- **Source:** [Nobel Prize API](https://www.nobelprize.org/about/developer-zone-2/)  
- **Columns include:** 'year', 'category', 'prize', 'motivation', 'prize_share', 'laureate_id',
       'laureate_type', 'full_name', 'birth_date', 'birth_city',
       'birth_country', 'sex', 'organization_name', 'organization_city',
       'organization_country', 'death_date', 'death_city', 'death_country',
       'is_female', 'us_born' and 'decade'.

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/nobel-prize-analysis.git
## How to Use

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/nobel-prize-analysis.git
2. Navigate to the project folder:

   ```bash
   cd nobel-prize-analysis
3. Open the Jupyter Notebook or Python scripts to explore the dataset and analyses.

## Visualizations

The project contains several plots, including:
Proportion of US-born laureates by decade
Proportion of female laureates by decade and category
Lists of repeat Nobel Prize winners

Done by @olguncelikel
