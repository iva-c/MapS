# MapS
Project for Roche Hackathon on multiple sclerosis

Authors: Primož Knap and Iva Černoša

> [!NOTE]
> This solution was awarded a prize

**MapS - a map for people with multiple sclerosis**

The goal of this project was creation of a map of Ajdovčšina (where the hackathon took place) with all obstacles and infrastructure relevant for patients with multiple sclerosis. Additionally, we created a heatmap grading locations based on surrounding infrastructure. 

We collected information about obstacles, pharmacies, benches, water points, stores and other relevant infractructure from OpenStreetMap API. A full list of selected features is avalible in _/data/selected_map_features.json_. We groupped the features into logically layers and created a custum Google Maps. 

# data_colection

Scripts used for collection of location data. 

# data

Infrastructure locations datapoints. 

# maps

Script used to make a heatmap and screenshots of layers in the costum Google Maps. 

