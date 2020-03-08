# Introduction

This is the template repository for the third assignment of Software Evolution 2019-2020. 
This repo contains the dataset on which you should run your statistical analysis, and
this readme contains the list of requirements the repository you submit to Canvas should satisfy. 

# Dataset

The dataset is available in the `./data` directory of the repository. Each file is compressed
as a `.gz` file (use 7Zip on Windows to expand). This is due to the fact that GitHub
imposes size restrictions on the size of individual files. Documentation on each of the
individual files can be found here:

- [code_reviews.csv](https://review.opendev.org/Documentation/json.html#change)
- [code_review_patch_sets.csv](https://review.opendev.org/Documentation/json.html#patchSet)
- [code_review_patch_set_comments.csv](https://review.opendev.org/Documentation/json.html#patchsetcomment)
- [code_review_comments.csv](https://review.opendev.org/Documentation/json.html#message)
- [code_review_approvals.csv](https://review.opendev.org/Documentation/json.html#approval)
- [patch_set_files.csv](https://review.opendev.org/Documentation/json.html#file)

# Submission requirements

When handing in your project please ensure it satisfies the following requirements:

- You should submit all code files required to process the input data and fit the models.
- The total size of the .zip file you submit should *not* be larger than 5MB. This means 
that you will not be able to include the raw data files in the `./data` direcotry in your 
submission. 
