# Example for external contributions to OGGM-Edu

In this repository, we illustrate how you can create your own educational content (in a notebook) and run it
in an OGGM / MyBinder environment.

There are two steps:

**1. Create your content and put in on an online repository**

**2. Create and share the link as explained below.**

## How to create a link

The link must have the following syntax:

`https://mybinder.org/v2/gh/OGGM/oggm-edu-r2d/master?urlpath=git-pull?repo=<PATH/TO/YOUR/REPO>`

For example, here is the link to this repository:

https://mybinder.org/v2/gh/OGGM/oggm-edu-r2d/master?urlpath=git-pull?repo=https://github.com/OGGM/oggm-edu-contrib

**To open in a jupyter-lab instead**, use:

`https://mybinder.org/v2/gh/OGGM/oggm-edu-r2d/master?urlpath=git-pull?repo=<PATH/TO/YOUR/REPO>%26amp%3Burlpath=lab/tree/<YOUR_REPO_NAME>`

**To open in a jupyter-lab and at a specific folder/file**, use:

`https://mybinder.org/v2/gh/OGGM/oggm-edu-r2d/master?urlpath=git-pull?repo=<PATH/TO/YOUR/REPO>%26amp%3Burlpath=lab/tree/<YOUR_REPO_NAME>/<PATH/TO/FILE>`

For example, this opens the test notebook in Jupyter Lab:

https://mybinder.org/v2/gh/OGGM/oggm-edu-r2d/master?urlpath=git-pull?repo=https://github.com/OGGM/oggm-edu-contrib%26amp%3Burlpath=lab/tree/oggm-edu-contrib/getting_started_with_contrib.ipynb

