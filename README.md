# BIG DATA ANALYTICS ASSIGNMENTS #
Assignments as given in the course of CSE545.

### Blog Corpus Industry Mention count using Spark: ###
#### Assignment 1: ####
_Dataset: http://u.cs.biu.ac.il/~koppel/BlogCorpus.htm_  
In this assignment, we were supposed to parse the blog corpus and run on spark to 
  1. Find all the industries.
  2. Get the number of times a industry was mentioned in all the blogs

### Satellite Image Analysis to find similar regions using Spark and AWS ###
#### Assignment 2: ####
_Dataset: https://lta.cr.usgs.gov/high_res_ortho_  
The goal of the assignment was to find similar regions in Long island using satellite image and running the code as in AWS.

Objectives:
1. Implement Locality Sensitive Hashing to find similar regions.
2. Implement dimensionality reduction to reduce the size of the images.
3. Preprocess the data to split and reduce the resolution of the images, flatten them, calculate the intensity and clip the image values.

Here I used Incremental SVD as proposed in  
"Sarwar, Badrul, et al. "Incremental singular value decomposition algorithms for highly scalable recommender systems." Fifth International Conference on Computer and Information Science. Citeseer, 2002."
