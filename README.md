![Movie-Theater](./images/movie_theater.jpg)

# The Path to Blockbuster: Navigating the Journey to Box Office Success

**Authors**: David Johnson and Norman Jen

## Overview

This project analyzes the profitability of different film genres at the box office. By examining the performance of various genres in terms of revenue generation, we aim to identify which types of films are currently experiencing the greatest success in the market. This analysis involves studying box office data to understand the financial performance of different genres and their respective profitability metrics. The goal is to provide actionable insights to the head of the company's new movie studio, enabling informed decision-making regarding the types of films to create in order to maximize commercial success.

## Business Problem

![Movie-Set](./images/movie_production_set.jpg)

The business problem is to determine the optimal strategy for a new movie studio targeting the US market. This involves identifying the most profitable genre of film to produce, as well as the key writers and directors with a track record of success in that specific genre. Additionally, the studio needs to determine the most lucrative time of year for movie releases in terms of profitability. By addressing these questions, the studio aims to maximize its chances of commercial success and establish a strong presence in the competitive US film industry.

## Data

In this analysis, data was sourced from [IMDb](https://www.imdb.com/) and [The Numbers](https://www.the-numbers.com/). The IMDb dataset provides comprehensive details on movies produced between [beginning year] and [end year], encompassing information on writers, directors, genres, country of origin, and average ratings for each film. Conversely, the Numbers dataset offers insights into box office performance metrics, such as production budgets and gross domestic revenue. Integrating these datasets offers a holistic understanding of movie performance, enabling analysis of factors influencing box office success.

, including the impact of writers, directors, genres, and budget allocations on profitability.

## Methods

This project uses descriptive analysis. This will provide a useful overview of how successful a movie is.

## Results

Over the years 1986 to 2007, the analyzed aircraft models, including the Cessna 150, Cessna 152, Cessna 172, and Piper PA-28, exhibited a consistent decrease in total fatalities, reflecting advancements in safety measures and technology. Among the four-seaters, the Cessna 172 showed fewer fatal injuries than the Piper PA-28, while in the two-seater category, the Cessna 152 demonstrated improved safety compared to the Cessna 150.

![Fatalities_YOY_by_Model](./images/fatalities_YOY_by_model.png)

The Cessna 152 stands out with the highest overall survival rate at 89.63%, indicating a relatively higher likelihood of passengers and crew surviving incidents. In contrast, the Piper pa-28 shows a slightly lower overall survival percentage at 79.90%, suggesting a comparatively lower average survival rate. The Cessna 150 and Cessna 172 fall within a similar range, both around 87%, indicating comparable safety performance. These brief observations highlight differences in safety outcomes among the selected aircraft models.

![Dead_or_Alive_by_Model](./images/doa_percent_by_model.png)

The comparative analysis of instructional and personal flights reveals a consistent safety trend in instructional flights throughout the year, with a minor peak in February. In contrast, personal flights exhibit higher fatalities during summer months, emphasizing the importance of season-specific risk assessments for flight planning.

![Fatalities_by_month.png](./images/Total_Fatalities_by_Month.png)

These visuals can be viewed [here](https://public.tableau.com/views/AviationIncidentAnalysis/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link) on our interactive Tablaue dashboard.


## Conclusion

This analysis leads to four recommendations for starting our movie production business:

- **Invest in a Cessna model aircraft.** The Cessna 152 stands out with the highest overall survival rate at 89.63%, followed closely by the Cessna 150 and 172 at ~87%. The Piper pa-28 showed the lowest overall survival percentage at 79.90%. 
- **Pay a little extra for a newer model plane.** Technology has evolved drastically since the inception of all these models of interest, and it is clear that over the years these planes have shown themselves to be safer.
- **Tailored risk assessments for flight planning.** Instructional flights consistently maintain lower fatality rates throughout the year, with a minor peak in February, while personal flights show a distinct seasonal pattern, peaking in fatalities during summer months (April and August). Flight planning considerations suggest scheduling instructional flights year-round and personal flights, preferably from October to March.
- **Open first location somewhere in the midwest region.** the Midwest region consistently exhibits the lowest number of fatalities compared to other continental U.S. regions. Additionally, the Midwest region stands out for having the highest average number of survivors, underscoring its positive safety record in aviation incidents.

### Next Steps

Further analyses could yield additional insights to how we can further improve our movie production business:

- **Determine the best location based on stakeholder preference.** We would need to explore real estate costs and then determine whether leasing or purchasing would be most ideal along with analyzing competition.
- **Determine overhead costs.** We would need to determine overhead costs such as planes, cost around employing experienced certified instructors, government regulations, and upkeep. Additional research around profit/loss/cost would need to be assessed along with understanding FAA requirements and exploring government regulations.
- **Analyze weather conditions in location choice.** We would need to further analyze how weather impacted fatalities in the seasons in order to determine when would be most ideal to promote instructional classes.

## For More Information

See the full analysis in the [Jupyter Notebook](./notebooks/final.ipynb) or review this [presentation](./movie_analysis_presentation.pdf).

## Repository Structure

```
├── images
├── zippedData
├── README.md
├── movie_analysis_presentation.pdf
└── movie_analysis.ipynb
```