# Web-Design-Challenge
For this homework assignment, creating a website by using visualizations that were created in Python-APIs homework. Github link: https://github.com/JW202/Python-API-Challenge/tree/main/WeatherPy/output_data

To build this dashboard, create individual pages for each plot and a way to navigate between them. These pages will contain the visualizations and des. Need to also build a landing page to provide a comparison of all the plots, along with another page to present the data used to build them.

### Website Requirements


The website must consist of seven pages in total, including:

1. A [landing page](#landing-page) containing the following elements:

  * An explanation of the project

  * Links to each visualizations page. There should be a sidebar containing preview images of each plot. Clicking an image should take the user to that visualization.

2. Four [visualization pages](#visualization-pages): Temperature, Humidity, Cloudiness and wind Speed, each with the following elements:

  * A descriptive title and heading tag.

  * The plot or visualization for the selected comparison (latitude vs: max temperature, humidity, cloudiness, or wind speed). The images displayed on these pages should be stored in the `assets/images` folder.

  * A paragraph describing the plot and its significance.

3. A ["Comparisons" page](#comparisons-page) that does the following:

  * Contains all of the visualizations on the same page so they can easily be compared with each other.

  * Uses a Bootstrap grid for the visualizations.

    * The grid must be two visualizations across medium and large screens, and it must be one visualization across on extra-small or small screens.

4. A ["Data" page](#data-page) that displays a responsive table containing the data used in the visualizations.

  * The table must be a Bootstrap table component. Refer to the [Bootstrap documentation](https://getbootstrap.com/docs/4.3/content/tables/#responsive-tables) for how to use responsive tables. 

  * The data must come from exporting the `.csv` file as HTML or by converting it to HTML. Try using a tool that you already know: Pandas. Pandas has a method, appropriately called `to_html`, that allows you to generate an HTML table from a Pandas DataFrame. To learn more, review the [documentation](https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.to_html.html).


Landing Page:

![Landing page large screen](landing.png)

Comparison Page:

![Comparison page large screen](comparison.png)

Plots:

![Plots with 4 choices](plots.png)

Data:

![Data page](data.png)
