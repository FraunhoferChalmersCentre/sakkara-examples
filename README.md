# Sakkara examples

In this repository, notebooks with examples of the [Sakkara](https://github.com/FraunhoferChalmersCentre/sakkara)
framework are gathered. There are currently 3 notebooks:

1. [Basics of Sakkara](1_basics.ipynb) <br /> Basic features of Sakkara, such
   as `DistributionComponent`, `Likelihood`, and assigning components do different hierarchical levels, exemplified by a
   mixed model.
2. [Data fusion](2_data_fusion.ipynb) <br /> Example on how to combine multiple data sources, despite
   irregular and non-synched sampling. Introduces `GroupComponent`
3. [`Nan` observations](3_nan_observations.ipynb)<br /> Inference for a state-space model with inputs, e.g.
   dependent observations, and `Nan` in observations. Introduces `FunctionComponent` and `DeterministicComponent`.

Full documentation of Sakkara is available at https://sakkara.readthedocs.io/