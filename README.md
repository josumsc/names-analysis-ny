# Names Ocurrence and Origins through the state of NY
*Source of the data to be traced to https://health.data.ny.gov/Health/Baby-Names-Beginning-2007/jxy9-yhdk*

## Aim of the Analysis
Which name is more present in the NY State? Do boys and girls names have the same spectrum, or does a gender tend to gather most of its personas around a subset of names? Are there any cultural or demographical reasons behind these names? All of these questions and more are expected to be answered thanks to the analysis performed here, using Python and its useful libraries to determine if there is any reason behind the distribution, both in time and space, of the names around one of the most famous states of probably the most notorious countries in the world.

## Structure of the Files
- **data/**:  Where a copy of the files used in the analysis is located
- **src/**: Code used during the analysis
- **img/**: Image/s used to illustrate better the results
- **names-analysis-ny.yml**: YML file to be installed through conda to replicate my environment.
- **LICENSE**: GNU GPL v3 license

## Environment installation
In order to recreate the environment used during this test one may refer to the [oficial Anaconda documentation](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file), which basically states that the correct way should be to execute in the terminal the following command while pointing to this very same directory:

```shell
conda env create -f names-analysis-ny.yml
```

In case you do not have Anaconda installed on your computer, you may download it [here](https://www.anaconda.com/products/individual) or use any other package management system such as [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/)
