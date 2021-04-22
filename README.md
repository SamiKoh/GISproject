# GIS project

## LUT Course Work

This GIS project examines city bike rides in Helsinki and Espoo during 2020.

Project is heavily focused on data wrangling and visualization. Main questions:

- Where do bike rides take place?
- How long is a typical ride?
- Which route is the most popular?
- What is the duration of that route?

Open data from HSL service dev.hsl.fi/citybikes/od-trips-2020/od-trips-2020.zip

Jupyter Notebook `project.ipynb` contains all of the analysis, `project.html` is an HTML
export from that notebook.

User can create a new Python 3 environment with required packages in Anaconda by calling
`conda create --name <env> --file requirements.txt`

Project uses data from publicly available open data services by HSL, Maanmittauslaitos and
OpenStreetMaps. Required data is provided in this private repository until this project
has been evaluated, after which it will be removed from this repository and its git history.
