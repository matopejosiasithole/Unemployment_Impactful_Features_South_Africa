### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

1. Install the WBGAPI: A new python package for accessing World Bank data, installation instructions available [here](https://pypi.org/project/wbgapi/)

2. Install Shaply , installation instructions available [here](https://shap.readthedocs.io/en/latest/)

3. There should be no additional libraries, beyond WBGAPI and Shaply, to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

For this project as part of UDACITY Data Science Nanodegree program submission, I was interestested in understanding South Africa's unemployment rate and its top contributing factors from the World Bank Group JOBS Dataset

1. Features with an 80 percent correlation to the target variable.
2. Training a linear model with the 80 percent correlated features and determining feature importance from Shaply values.
3. Draw an understanding from the impactful features from the Shaply values.

## File Descriptions <a name="files"></a>

There is 1 notebook available here to showcase work related to the above project understanding requirement.  The notebook uses World Bank JOBS dataset for South Africa and uses this data to understand important features for the target variable, 'Unemployment, total (% of total labor force) (modeled ILO estimate)'.  

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@matopesithole/understanding-south-africas-unemployment-top-contributing-factors-from-the-world-bank-group-jobs-661bf1a19d07).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Credit is given to the following resources, which were used for this project.

1. WORLD BANK GROUP for the data. link: [here](https://databank.worldbank.org/source/jobs).
2. WBGAPI for accessing the data. Link: [here](https://pypi.org/project/wbgapi/)
3. UDACITY - Data Science Nanodegree Course Content
