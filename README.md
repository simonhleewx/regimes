This repository contains various Jupyter Notebooks and Python code which compute weather regimes, in various different ways/domains.

The notebooks "north_american_winter_regimes" and "north_atlantic_winter_regimes" use a straightforward method for computing DJFM regimes using ERA5, and can be adapted to other domains.

The notebook "runningmean_compute_year_round_namerica_regimes" uses the year-round method of Lee et al. (2023, J. Climate) but with a running mean instead of a Fourier filter, which gives similar results and is more easily applied to model data. The domain can also be changed to produce similar regimes elsewhere (e.g. N Atlantic).
