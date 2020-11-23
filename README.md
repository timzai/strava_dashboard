# FIT file Heart Rate Dashboard

This dashboard provides heart rate zone data to help users review their workout sessions.

Heart rate zone information is superimposed on the following visualizations as colors:

* Map of workout
* Heart rate over time
* Distribution of heart rate zones
* Speed
* Cadence
* Altitude

## Configurable Options

Users can select their sessions according to FIT files.

Users can configure their own heart rate zones and color representations.


## Data

The `data` folder is not included because it cannot be redistributed.

Place .fit files ("Fitness Interchange Format") in the `data` folder and run dashboard.ipynb for the dashboard

## Packages and Versions

```
pandas 1.1.1
numpy 1.19.1
folium 0.11.0
plotly 4.12.0
jupyter_dash 0.3.0
fitparse 1.1.0
dash 1.17.0
```