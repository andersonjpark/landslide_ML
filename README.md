# Landslide Machine Learning

## Applying Machine Learning to the dataset

Applying algorithms to the dataset to find out the geolocation of cities that needs better preparation on landslides. It is found based on the fatalities proportional to the size of the landslide.

Source: https://data.nasa.gov/dataset/Global-Landslide-Catalog-Export/dd9e-wu2v/data

## Procedure

## What should be done

1. Digging the number of fatalities at multi-angle (population, landslide_size, distribution, clusters) for better analysis.
2. Modifying the latitude and longitude calculation while clustering (considering that earth is a sphere)
3. Find the best number of clusters using kmeans.score() (so far I just set the number of cluster as 5)
4. Increasing the size of the dataset
5. Adding scatter plot of the clustering for visualization [DONE]
