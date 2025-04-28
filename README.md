# Song Cluster

## Overview

This repository contains the analysis and clustering of songs based on their audio features. The project aims to identify patterns and group similar songs together to help understand musical preferences and potentially build recommendation systems.

## File Structure

The repo is structured as:

* **data/raw_data** contains the raw song data as obtained from music platforms or datasets.
* **data/analysis_data** contains the cleaned and processed dataset that was constructed for analysis.
* **models** contains fitted clustering models and their evaluation metrics.
* **other** contains relevant literature, details about LLM chat interactions, and sketches.
* **paper** contains the files used to generate the paper, including the Quarto document and reference bibliography file, as well as the PDF of the paper.
* **scripts** contains the scripts used to download, clean, and analyze the song data.

## Statement on LLM usage

[Include information about any LLM tools used in your project. For example:]
Aspects of the code were written with the help of GitHub Copilot. The data preprocessing steps were developed with assistance from ChatGPT, and the entire chat history is available in inputs/llms/usage.txt.

## Methods

The project uses unsupervised learning techniques, primarily clustering algorithms like K-means and hierarchical clustering, to group songs based on audio features such as tempo, energy, danceability, and acousticness. Feature engineering and dimensionality reduction techniques are applied to improve clustering results.

## Results

[Include a brief description of your findings here once available]

## References

[Include references to datasets, methodologies, or other resources used]
