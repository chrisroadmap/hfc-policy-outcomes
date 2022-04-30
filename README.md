# HFC Policy Outcomes
Determining the climate response to outcomes of future HFC emissions for air conditioning.

## Reproduction

This assumes that you are using `anaconda` and `python` 3.7+.

1. Clone the repository locally with `git clone git@github.com:chrisroadmap/hfc-policy-outcomes.git`. If you don't have `git` available and don't plan to do any development, downloading a tarball of the repository should also work.

2. Create the conda environment:

```
conda env create -f environment.yml
```

Optionally, you can override the default environment name (`hfc-policy-outcomes`) by passing a `-n your-env-name` flag if you want to call it something different.

3. Activate the environment with `conda activate hfc-policy-outcomes`.

4. FOR DEVELOPERS: If you plan to develop the notebooks with a view to merge into the main fork (`chrisroadmap/hfc-policy-outcomes`), I will require version-control friendly notebooks, which will remove all output and data upon committing. To do this, run
```
nbstripout --install
```

If you don't plan to make changes and just want to reproduce (or won't be pushing your changes to GitHub) this step isn't required.

If you need to add more dependencies to the `conda` environment, edit the `environment.yml` file and run `conda env update -f environment.yml --prune`.

5. Run the `notebooks` in numerical order.

## Questions

Please raise an issue if you run into difficulties.
