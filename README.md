# LDS-EM
Linear dynamic system fit with expectation-maximization algorithm.

Based on the [pykalman](https://github.com/pykalman/pykalman) implmentation with two major contributions:
- Generalized EM to train on batches of observations rather than a single sequence.
- Added a version of LDS model with time-varying transition matirx
