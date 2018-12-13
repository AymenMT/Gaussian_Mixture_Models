# Gaussian_Mixture_Models
Expectation-Maximization algorithm for Gaussian Mixture Models

During this Practical work, we are going to first generate data following a GMM model, and then we are going to implement an EM algorithm in order to infer the GMM model parameters. First, let's introduce a GMM model :

A Gaussian mixture model is a probabilistic model that assumes all the data points are generated from a mixture of a finite number of Gaussian distributions with unknown parameters. One can think of mixture models as generalizing k-means clustering to incorporate information about the covariance structure of the data as well as the centers of the latent Gaussians : 


$$ X_i &\sim GMM(\mu_{1:K}, \Sigma_{1:K}, \pi_{1:K}) $$

With : 

* K : number of gaussian

* $$\mu_{k}$$ : mean of the kth gaussian

* \Sigma_k : cov matrix of the kth gaussian

* \pi_k : weight of the kth gaussian, \sum_{k=1}^{K} \pi_k = 1
