
# `bayesian_priors`

a package for visualizing prior distributions in the context of bayesian inference. The following continuous distributions are supported: normal, student-t, exponential, gamma, inverse gamma, weibull, pareto, gumbel, log-normal, cauchy, beta. In the dashboard, user inputs their desired lower and upper bounds, along with the % mass in-between. The dashboard will then display a set of  parameters that generates such distribution.

```python
import bayesian_priors

bayesian_priors.dashboard(description=True)
```
