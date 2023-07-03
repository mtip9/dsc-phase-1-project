# Movie Studio Analysis

**Author**: [Michael Tsypin](email:mtsypin9@yahoo.com)

## Overview

The purpose of this project is to analyze how films performed at the box office, and use data to find which are the most successful and why. This project focuses on "Return on Investment" (ROI) as a measure of a film's success across data types including; the month a film was released, length of film, and film genre.

## Business Problem

Microsoft has decided to venture into the film industry, but they need some insight on how to create profitable projects. Through research, we can analyze successful films in the past to deteremine what would help Microsoft excel above their competitors. By collecting data from a wide variety of films, we can provide Microsoft recommendations on how they can produce the most successful films.

## Data and Methods

Access to data of over 1000 films from over the past 100 years. Types of data for each film includes production budget, worldwide gross, release date, runtime minutes, and genres. Values from production budget and worldwide gross can be used to calculate ROI and use this value as a measure of success.

## Results

Films released in the months of July, August, and November have had the greatest ROI.

![ROI per Month](https://github.com/mtip9/dsc-phase-1-project/blob/master/Images/ROI%20per%20Month.png)

Films with runtime of 90 minutes or less have the greatest ROI and also cost less

![ROI per Movie Length](https://github.com/mtip9/dsc-phase-1-project/blob/master/Images/ROI%20per%20Movie%20Length.png)

Genres of dramas, horrors, and thrillers are the most represented and profitable genres within the top 100 films within the Top 100 ROI dataframe

![Top Genres in Top 100 ROI](https://github.com/mtip9/dsc-phase-1-project/blob/master/Images/Top%20Genres%20in%20Top%20100%20ROI.png)

## Recommendations

The analaysis of films above provides three recommendations for Microsoft:

- Films should be released in the months of July and August. These months have the greatest ROI compared to the other months of the year.

- Films should be made with runtimes of 90 minutes or shorter. There is a correlation between production budget and movie length; the shorter a film is, the lower the budget. By making a film under 90 minutes, not only is less money required to make the film, data suggests that there will be a greater return on investment.

- Films made by Microsoft should either be dramas, horrors, or thrillers. These three genres are the most profitable genres found in the dataframe of top 100 films categorized by ROI.

## Next Steps

- Source actors/actresses that have been successful in past films. We can research some of the best in the industry to produce a top grossing film.

- Explore soundtracks that have increased popularity in a film. A films popularity can greatly increase by the traction the soundtrack gets. Doing research on past soundtrack artists and producers can help a film shine.

- Find directors associated with successful films. Directors can make or break a films success. By exploring top grossing directors, Microsoft can recruit the best to produce their films.

## For More Information

See the full analysis in the [Jupyter Notebook](Movie_Studio_Analysis.ipynb) or review [Presentation](Movie_Studio_Presentation.pdf)

## Repository Structure

```
├── Images
├── zippedData
├── Movie_Studio_Analysis.ipynb
├── Movie_Studio_Presentation.pdf
└── README.md
```
