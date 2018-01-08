# Landslide Machine Learning

## Applying Machine Learning to the dataset

Applying algorithms to the dataset to find out the geolocation of cities that needs better preparation on landslides. It is found based on the fatalities proportional to the size of the landslide.

Source: https://data.nasa.gov/dataset/Global-Landslide-Catalog-Export/dd9e-wu2v/data

## Procedure

## What should be done

1. modify the latitude and longitude calculation while clustering( Consider earth is sphere)
2. Find the best number of clusters (So far I just set # of cluster =5)
3. Using groupBy function for multiple fields(landslide_size & fatalities) and comparing
4. Increase the size of the dataset
5. Adding scatter plot of the clustering for visualization
