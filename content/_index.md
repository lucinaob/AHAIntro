---
title: AHA Visualization Project
---

## What is the AHA Visualization Project?

The American Historical Association (AHA) Visualization Project is a research project that aims to catalog and visualize data on the AHA's annual meetings, dating back to the 1800s. The AHA is the oldest professional association of historians in the United States and one of the largest in the world. Because of this, it's annual meeting serves as one of the largest data sources to understand what American historians have been studying for nearly 150 years. Additionally, we can collect data on which institutions send historians to the AHA. By collecting this data, we can gain a deeper understanding of how the field of history has evolved and expanded.

This project is not associated with or funded by the AHA. It is supported by Smith College history professor Joshua Birk and his [CODEX Medieval History Lab](https://sites.smith.edu/medievalhistoryresearchlab/). All work has been done by Smith College students.

## Data Sources and Method

All data for this project was taken from the [AHA's official site](https://www.historians.org/events/annual-meeting/past-meetings/) and archived versions of previous meetings' sessions.

Meetings previous to the early-to-mid-2000s are only available as PDF versions of the original meeting programs. Because of their varying quality and layouts, the easiest way to collect these data is through manual entry, rather than scraping the data. Our team created extensive spreadsheets that would collect the session names, paper names, participating institutions, the type of session (e.g., panel, paper presentation, luncheon), and any affiliated professional societies. Additionally, we manually matched institutions to geolocation data, including the city, country, and coordinates of the institution. For American institutions, we also recorded the state and region of the institution. 

More modern meetings' sessions are available online. Our team developed a web-scraping method using R, which we then manually cleaned. This method collected data on session names, paper names, participating institutions, the type of session, and any affiliated professional societies. 

## Analysis

# Geolocation (multiple years, 1975-85? or 60s? when there's more data)

  # map, gif?
  
  # histogram

# Topics

  # Topical index, 1975
  
  # keywords (most popular words in papers/panels/etc), some 2010s stuff
  
  # future goals
  
  
# Website goals

- The data set, sources and ways of collecting data
    - manual
    - webscraping
- what we can do with this data
    - topical index
        - specify that going forward we want to make our own way of cataloging
    - geolocation data
        - similar visualizations as collaborations
        - stretch: goal for diff years
- goal: interactive and accessible database


<hr />
