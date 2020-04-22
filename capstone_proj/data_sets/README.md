### Datasets

#### Background

This directory contains PA crash data filetered on the unbelted variable. Originally I had planned to use the full sets and normalize the values with OpenRefine. However, I ran into an issue with the files being too large and not being able to be loaded by the tool. I used the gshuf tool to randomly the sample the files to contain row counts of 10k, 5k, 1k, and 500.
Only the files with 500 rows were able to be loaded by OpenRefine. While this is disappointing, I was able to use an online tool to calculate a statistically repsresentative sample size. For the belted data set this came out to around 243 rows, meaning that my set has twice the number needed to statistically represent the whole set.

#### Contents
* `/normalized_data` contains both belted and unbelted datasets normalized and edited within OpenRefine
* `sampled_data' contains both belted and unbelted datasets sampled from the larger files but unprocessed
* `openrefine_proj_files` contains the exported OpenRefine project files
* `operation_history_captsone.json` is the json file that contains the history and operations done within OpenRefine