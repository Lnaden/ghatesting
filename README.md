# Repo to test conda-incubator/setup-miniconda and channels in env file

This repo tests an edge case found in GitHub Actions conda-incubator/setup-miniconda where 
empty `channels` in the conda environment YAML file cause the GHA to break with an unhelpful
error.

Tests the permutations of:
* In File: Channels defined / Channels empty / Channels undefined
* In GHA: Channels undefined / Channels defined 

6 Permutations.

# This also tests other GitHub actions
