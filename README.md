# Visual-Search-of-Garments
Finding Visually Similar Garment for the Garments input
This repository contains a jupyter notebook and finding 10 visual similar garments
In order to extract features from the pictures database, I used the resnet50 architecture. I have eliminated the final completely connected and avgpool layer in order to extract a feature vector of size (2048,7,7).
