# Distribution modelling

Using python to fit left bound zero inflated (or not) data with a Poisson distribution (ZIP).

## Other Bounded distributions
See a complete list here: https://www.vosesoftware.com/riskwiki/Selectingtheappropriatedistributionsforyourmodel.php 

### *Continuous*
- Chi or Chi Sqaured
- Exponential
- F
- Gamma
- Log distributions (normal, gamma, Laplace, logistic etc.)
- Weibull

### *Discrete*
- Logarithmic
- Poisson
- Geometric
- *Binomial*

## Datasets

### ToxEvents

Data to be added by @AlexandreDeletang
Dataset description: 
- Discrete (integers only)
- Partially bounded (above zero) - perhaps **zero inflated**
- Maybe best with non-parametric (emprical) distribution
- Univariate first order distribution

### Dataset Poisson

**Dataset**: Simply generate the Poisson data using a poisson model

If the distribution looks like a Poisson distribution with extra zeros it may be appropriate to use the ZIP model (**zero inflated poisson**)
**Dataset ZIP**: take the same generate but add zeros manually