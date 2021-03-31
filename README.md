# Housing Analysis Project

**Author**: Sierra Stanton

## Overview
![Github Repo Size](https://img.shields.io/github/repo-size/sierrafromcalifornia/Film-Analysis-Project?style=social)
![Github Follow](https://img.shields.io/github/followers/sierrafromcalifornia?style=social)
![Twitter Follow](https://img.shields.io/twitter/follow/sierrastanton?style=social)

This project analyses the housing industry as we compile valuable intel for homeowners considering whether home improvement projects will add value to the sale value of their homes. We have been charged with helping a client in King County, WA forecast the potential monetary effects of particular home improvement projects in their county. We'll use X datasets to TBD.

![Home Improvement](/references/images/90s-home-improvement-tim-allen-8Rf3xSwC1R39u.gif)


## This Repository

### Repository Structure

```
├── README.md        <-- Main README file explaining the project's business case,
│                        methodology, and findings
│
├── data             <-- Data in CSV format
│   ├── processed    <-- Processed (combined, cleaned) data used for modeling
│   └── raw          <-- Original (immutable) data dump
│
├── notebooks        <-- Jupyter Notebooks for exploration and presentation
│   ├── exploratory  <-- Unpolished exploratory data analysis (EDA) notebooks
│   └── report       <-- Polished final notebook(s)
│
├── references       <-- Data dictionaries, manuals, and project instructions
│
└── reports          <-- Generated analysis (including presentation.pdf)
    └── figures      <-- Generated graphics and figures to be used in reporting
```

### Quick Links

1. [Final Analysis Notebook](notebooks/exploratory/final_notebook.ipynb)
2. [Presentation Slides](reports/presentation.pdf)

### Setup Instructions


## Business Understanding

A client in King County, WA wants to advise homeowners on home improvement projects that will add to the sale value of their homes.

These three claims can be addressed directly with the three datasets (from the King County Department of Assessments) described later in this document:

1. Enclosing a porch will increase the sale price of a home.1
2. Converting a garage to a bedroom is a good way to increase the sale price of a home.2
3. Upgrading to a forced-air heating system will increase the sale price of a home.3,4

Your task is to build a linear regression model to represent home sale prices in King County, and use it to advise homeowners on which home improvement projects will add to their home sale values.

## Data Understanding

Data will be used from the following:
* **Parcel Records** - shows us details regarding each unit of land that has been created by a partitioning of land
* **Residential Building Records** - shows us a breakdown of attributes pertaining to building records
* **Real Property Sale Records** - details land, everything that is permanently attached to the land, and all of the rights of ownership
* **Look Up** - shows us serves as a dictionary, providing two sets of identifying numbers that equate to real-world information about land.


## Data Preparation

TODO: add data preparation (which can be quite brief, but make sure you explain any dropped records)

![Correlation](/references/images/home-attributes-correlation.png)

This image shows which particular home features are most proven to affect the resulting sales price of a home.

## Modeling

TODO: add modeling.  What are the features of your final model?

## Methods & Results

We extracted and cleaned residential building records in order to build increasingly effective linear regression models that infer the relationships between elements of homes and their associated prices. We also compared which elements had the most dramatic effect on said prices in order to help our client properly advise home owners.


## Conclusion

TODO: add conclusion.  How does your model answer the business question?

* THE TOTAL SQUARE FOOTAGE OF A HOME IS PROVEN TO HAVE THE LARGEST BEARING ON THE HOMES RESULTING SALES PRICE
* THE DISTRICT OF EACH RESIDENTIAL HOME SHOWS TO BE INSTRUMENTAL IN DETERMINING THE RANGE OF SALES PRICE FOR A HOME, TO THE EXTENT THAT HOME PROJECTS COULD COST MUCH MORE THAN THE POTENTIAL SALES PRICE BUMP
* ENCLOSED PORCHES ARE MUCH LESS POPULAR THAN OPEN PORCHES AND ARE NOT RECOMMENDED FOR MONETARY GAIN

## Next Steps

## For More Information
