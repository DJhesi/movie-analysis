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

## Methods

This project uses descriptive analysis. This will provide a useful overview of how successful a movie is.

## Results

The data analysis reveals that Musicals and Animation films demonstrate the highest average domestic profits, with Musicals leading at approximately $5.2 million and Animation closely following at around $3 million. Additionally, Animation emerges as a lucrative genre on the global scale, with the highest average worldwide profit of approximately $2.5 million, and ranking second in average foreign profit at $2.4 million. Consequently, focusing on producing films in these genres presents the most promising opportunity for success and profitability in the movie industry.

![Profit_Genre](./images/fatalities_YOY_by_model.png)

The analysis of the graph reveals that movies released during the summer season garnered the highest average domestic profit, indicating that summer releases were the most profitable at the box office, with an average profit of approximately $1.8 million. The data suggests a correlation between the genre preference of Animation and Musical films, which often cater to younger audiences, and the profitability of summer releases. This trend aligns with the fact that summer months coincide with school vacations, making it an opportune time for families and children to attend movies, resulting in higher average domestic profits for these genres during the summer season.

![Profit_Release_Month](./images/doa_percent_by_model.png)

Among the top 10 Musical/Animation films by domestic profits, both Cinco Paul and Ken Daurio worked on three each, having written for the highly successful films "The Secret Life of Pets," "Despicable Me 2," and "Despicable Me 3." Given their involvement in writing for three of the top 10 profiting movies in this genre, we are confident in recommending them as writers for our film.

![Profit_Writer.png](./images/Total_Fatalities_by_Month.png)

Kyle Balda, Chris Renaud, and Pierre Coffin, each directed two of the top 10 Musical/Animation films by domestic profit. Specifically, Kyle Balda directed "Minions" and "Despicable Me 3," Chris Renaud directed "The Secret Life of Pets" and "Despicable Me 2," while Pierre Coffin directed "Despicable Me 2" and "Despicable Me 3." This track record underscores their proficiency in directing successful films within the genre.

![Profit_Director.png](./images/Total_Fatalities_by_Month.png)

These visuals can be viewed [here](https://public.tableau.com/views/AviationIncidentAnalysis/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link) on our interactive Tablaue dashboard.


## Conclusion

This analysis leads to four recommendations for starting our movie production business:

- **Focus on musical and animation films.** The analysis indicates that Musicals and Animation films exhibit the highest average domestic profits, with Musicals leading at $5.2 million and Animation following closely at $3 million, while Animation also proves to be a lucrative genre globally, with the highest average worldwide profit and ranking second in average foreign profit.
- **Release our movies during the summer time.** The analysis indicates that summer releases, coinciding with school vacations, garnered the highest average domestic profit, with Animation and Musical genres, appealing to younger audiences, particularly benefiting from this trend.
- **Choose writers with a proven track record.** Cinco Paul and Ken Daurio, having contributed as writers to three highly successful films within the top 10 Musical/Animation movies by domestic profits, including "The Secret Life of Pets," "Despicable Me 2," and "Despicable Me 3," are confidently recommended as writers for our film.
- **Choose directors with a proven track record.** Kyle Balda, Chris Renaud, and Pierre Coffin each directed two of the top 10 Musical/Animation films by domestic profit, showcasing their expertise in directing successful films in the genre, with notable works including "Minions," "The Secret Life of Pets," and the "Despicable Me" franchise.

### Next Steps

Further analyses could yield additional insights to how we can further improve our movie production business:

- **Find the best voice actors/singers.** To find the best voice actors/singers, we could potentially conduct focus group testing to gather feedback and insights on their performances, helping us identify the most suitable candidates for our project.
- **Budget planning.** Develop a comprehensive budget plan outlining expenses for pre-production, production, and post-production stages.
- **Marketing strategy.** Develop a marketing plan to promote the film and generate buzz leading up to its release.

## For More Information

See the full analysis in the [Jupyter Notebook](./movie_analysis.ipynb) or review this [presentation](./movie_analysis_presentation.pdf).

## Repository Structure

```
├── images
├── zippedData
├── README.md
├── movie_analysis_presentation.pdf
└── movie_analysis.ipynb
```