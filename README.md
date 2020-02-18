# Project Summary
----------------------
## Latitude - Latitude Analysis Dashboard with Attitude

This Project is about Creating a visualization dashboard website using Weather data using HTML, CSS, Boostrap, Pandas, and Matplotlib.

In building this dashboard,i created individual pages for each plot and a means by which we can navigate between them. These pages contain the visualizations and their corresponding explanations. I also created a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.


The website consist of 7 pages total, including:

  - A landing page containing:
  - Links to each visualizations page.
  - Four visualization pages, each with:
    - A descriptive title and heading tag.
    - The plot/visualization itself for the selected comparison.
    - A paragraph describing the plot and its significance.
  - A "Comparisons" page that:
    - Contains all of the visualizations on the same page so we can easily visually compare them.
  - Creating boostrap grid of two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
  - A "Data" page that:
    - Displays a responsive table containing the data used in the visualizations.
  - The data is exported from a .csv file as HTML using Pandas. 
  - The website has at the top of every page, have a navigation menu that:
    - Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
    - Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
    - Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
    - Is responsive (used media queries). 
