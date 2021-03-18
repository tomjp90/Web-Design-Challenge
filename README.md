# Web Design - Web Visualization Dashboard (Latitude)
This assignments aim is to create a visualisation dashboard website using visualisations created in a past assignment. Specifically, weather data and it's latitude is summarised on the site.

## Link to site
https://tomjp90.github.io/web-design-challenge/index.html

## Technologies used
* HTML
* CSS
* Bootstrap
* Python Pandas


## Latitude - Latitude Analysis Dashboard

In building this dashboard, it will create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualisations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Requirements

The website must consist of 7 pages total, including:

* A landing page containing:
  * An explanation of the project.
  * Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
* Four visualisation pages, each with:
  * A descriptive title and heading tag.
  * The plot/visualisation itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A comparisons page that:
  * Contains all of the visualisations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualisations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A data pade that:
  * Displays a responsive table containing the data used in the visualisations.

The website must, at the top of every page, have a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualisation page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive using media queries.
