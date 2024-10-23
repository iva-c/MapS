# MapS
Project for Roche Hackathon on multiple sclerosis

Authors: Primož Knap and Iva Černoša

> [!NOTE]
> This solution was awarded a prize

**MapS - a map for people with multiple sclerosis**

The goal of this project was creation of a map of Ajdovščina (where the hackathon took place) with all obstacles and infrastructure relevant for patients with multiple sclerosis. Additionally, we created a heatmap grading locations based on surrounding infrastructure to help the mmunicipality identify areas that need iimprovement. Weights used for the heatmap can be adjusted to other disabilities. 

We collected information about obstacles, pharmacies, benches, water points, stores and other relevant infractructure from OpenStreetMap API. A full list of selected features is available in _/data/selected_map_features.json_. We grouped the features into logically layers and created a custom Google Maps. 

# data_collection

Scripts used for collection of location data. 

# data

Infrastructure locations datapoints. 

# maps

Script used to make a heatmap and screenshots of layers in the custom Google Maps. 

