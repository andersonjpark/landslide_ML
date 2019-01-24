# Landslide Machine Learning

## The research objective of this proposal is to figuring out the reasoning of large number of fatalities on specific regions.

This project contains 3 parts.

1. Understanding the factors that lead to huge number of fatalities from landslide_size

2. Classifying regions by clustering. (Could be done from using countries in the dataset, but I want to take a step farther)

3. Visualizing the result by making an HTML that contains a world map and dots for each landslides. (The regions are distinguishable based on colors and size of the dots are based on the number of fatalities for that landslide.)


Part 1 will be supervised regression.

Part 2 will be unsupervised clustering.

Part 3 will be using the html already made from Landslide_visualization.

Source: https://data.nasa.gov/dataset/Global-Landslide-Catalog-Export/dd9e-wu2v/data

## What should be done

1. Digging the number of fatalities at multi-angle (population, landslide_size, distribution, clusters) for better analysis.
2. Modifying the latitude and longitude calculation while clustering (considering that earth is a sphere)
3. Find the best number of clusters using kmeans.score() (so far I just set the number of cluster as 5) [DONE]
4. Increasing the size of the dataset
5. Adding scatter plot of the clustering for visualization [DONE]
