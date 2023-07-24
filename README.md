# Microsoft-Movie-Analysis

**Author**: [Stacy Kiriiri](mailto:wkiriiri@gmail.com)

## Overview

This is a data analysis project conducted for Microsoft's new movie studio. The goal of this project is to analyze movie data
to provide actionable insights for Microsoft to decide what type of films to create.

## Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they do not know anything about creating movies. I was charged with exploring what types of films are currently doing the best at the box office. I had to translate those findings into actionable insights that the head of Microsoft's new movie studio
can use to make informed decisions about movie production.

## Data             

In the folder zippedData are movie datasets from:

[Box Office Mojo](https://www.boxofficemojo.com/),
[IMDB](https://www.imdb.com/),
[Rotten Tomatoes](https://www.rottentomatoes.com/),
[TheMovieDB](https://www.themoviedb.org/),
[The Numbers](https://www.the-numbers.com/)

These are the datasets used for analysis.

## Methods

This project uses exploratory data analysis to generate insights for the business stakeholder.

## Getting Started

To reproduce the analysis, you will need Jupyter Notebook, Python, and the required libraries. You can install the necessary libraries using the following command:

    pip install pandas matplotlib seaborn

To start the analysis, open Jupyter Notebook

## Results

The analysis yielded three concrete business recommendations for Microsoft:

- ** The popular genre according to the analysis is Documentaries.

     ![Popular Genre](/images/genre.png)

- ** The movies released between Q2 and Q4 are more popular.

    ![Popular Release Season](/images/season.png)
     
- ** The worldwide revenue is thriving more than the domestic revenue.

    ![Revenue](/images/revenue.png)

## Conclusions

- ** Microsoft movie studio should focus on producing documentaries as this genre appears to have a higher demand and audience appeal.

- ** Microsoft should strategically plan their movie release dates by considering the seasons or years that movies have a higher popularity.

- ** Microsoft should prioritize marketing efforts to promote movies locally as much as worldwide.



## Recommendations

- ** Microsoft should allocate resources such as budget and talent towards the popular genres based on the timelines that 
the genres are popular.

- ** Microsoft can release blockbuster movies during peak movie going seasons or timing release dates to coincide with holidays
or special events.

- ** Microsoft can negotiate with theatres to secure a high number of screens and prime showtimes for new movie releases to increase the domestic revenue.



## For More Information

See the full analysis in the [Jupyter Notebook](/student.ipynb) or review this [presentation](/presentation.pdf)

For additional info, contact Stacy Kiriiri at [wkiriiri@gmail.com](mailto:wkiriiri@gmail.com)

## Repository Structure

```
├── .ipynb_checkpoints
├── images
├── zippedData
├── README.md
├── presentation.pdf
└── student.ipynb
```