# Ideal_Location
Finding Ideal Neighbourhood in Toronto Ontario, for Good guys pizzah to create their next Pizzeria chain.

Using Machine Learning and Artificial Intelligence this project's purpose is to plot a map using folium to highlighting clusters of Neighbourhoods ranking their desirability.

## Data Collection
Collecting Data from various datasets that contains information on Toronto's Neighbourhoods:
- Neighbourhood Dataset
- Neighbourhood Profiles
- Neighbourhood Crime Rates
- Venues Collection

### Merging Neighbourhood Data
Shown below a dataset on the combination of neighbourhood data

![This is an image](https://github.com/Mohammad0336/Ideal_Location/blob/main/Images/Clusters.jpg)

### Foursquare Venue Data
Shown below a dataset on venues of pizza shops

![This is an image](https://github.com/Mohammad0336/Ideal_Location/blob/main/Images/VDataset.jpg)

### Cluster Data
Shown below a dataset created after grouping the merged venue and neighbourhood data

![This is an image](https://github.com/Mohammad0336/Ideal_Location/blob/main/Images/Clusters.jpg)

### Cluster Means
Means of cluster data

![This is an image](https://github.com/Mohammad0336/Ideal_Location/blob/main/Images/ClustersMean.jpg)

## Result
Final map representing the ideal venue location

![This is an image](https://github.com/Mohammad0336/Ideal_Location/blob/main/Images/Map.jpg)

When Examining the cluster means they were then ranked:

`Cluster1: Ranked 1st for idealism`: `Green Areas on Map`

`Cluster0: Ranked 2nd for idealism`: `Yellow Areas on Map`

`Cluster2: Ranked 3rd for idealism`: `Cyan Areas on Map`

`Cluster3: Ranked 4th for idealism`: `Red Areas on Map`

`Marker: Ideal Location Rouge Neighbourhood`

## Built using: 
- Neighbourhood Dataset: https://open.toronto.ca/dataset/neighbourhoods/ 
- Neighbourhood Profiles: https://open.toronto.ca/dataset/neighbourhood-profiles/
- Neighbourhood Crime Rates: https://data.torontopolice.on.ca/datasets/TorontoPS::neighbourhood-crime-rates-boundary-file-/about
- Foursquare Places API: https://developer.foursquare.com/reference/place-search
- Jupyter Notebook
- Folium
