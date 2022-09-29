# A graph-based Superframework for Mixture Model estimation using EM. An analysis of US wholesale electricity markets

by
Carlo Mari,
Cristiano Baldassari.


We propose a fully unsupervised graph-based Superframework to handle the EM initialization problem for estimating Mixture Models on financial time series. By using a complex network approach linking time series and graphs, we can exploit graph-structured information derived from the observed data and produce a meaningful starting point for the EM algorithm. We found that structural information derived by complex graphs can definitely capture time series behavior and nonlinear relationships between different observations. We applied the proposed methodology to estimate Gaussian Mixture Models on US wholesale electricity market prices using two different configurations of the Superframework. The obtained results show that our methodology performs better than conventional initialization methods, such as K-means and Random-based techniques. Moreover, the proposed approach has a high degree of generalization and flexibility, exploiting graph manipulation and employing functional operating blocks, which can be adapted to very different empirical situations.
