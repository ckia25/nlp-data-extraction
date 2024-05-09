# COS484 FINAL PROJECT by Caiden Kiani, Avi Attar, and Hugh Shields.

# Title: Strategies for Training Data Extraction from Large Language Models

## Content Description:

**top_n_generations:** This is a folder with all the data generated and used in the top_n experiment and the results from the membership inference sorting methods.

**url_generations:** This is a folder with all the URLs generated in the URL experiment. There is a separate CSV for each model.

**wiki_generations:** This is a folder with all of the CSV files from the wiki experiment. There is a CSV file for each model/prefix configuration. Each file has the prefixes, model output, reference texts, and consecutive matching token counts.

**experiments.ipynb:** This is the Python notebook that generated all of the samples using the model. The bulk of the project was running this notebook for many hours to produce 1000s of generations. 

**membership_inference.ipynb:** This is the Python notebook used to compute the sorting metrics for the top-n experiment.

**wiki_data.ipynb:** This is the Python notebook used to download the Wikipedia data and select the random wiki pages for the wiki experiment. Some of the code in this file was taken from https://github.com/noanabeshima/wikipedia-downloader


**wiki_results.ipynb:** This is a Python notebook that has code that helped generate the table results for the wiki experiment
