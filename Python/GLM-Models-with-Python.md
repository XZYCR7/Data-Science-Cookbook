
> Written with [StackEdit](https://stackedit.io/).

# GLM models in Python

## Different option to implement GLM models using Python
The following Python libraries provide GLM implementation using Python:
- scikit-learn
- h2o
- StatsModels
- TensorFlow
- PyTorch
- PySpark

### GLM with scikit-learn

- As at today you can only find there logistic and gaussian distributions implemented. 
- But really soon we are going to have the whole GLM family (Gamma, Poisson, Tweedie, etc.)

References:

- [Auto  examples linear model plot tweedie regression insurance claims](https://63035-843222-gh.circle-artifacts.com/0/doc/auto_examples/linear_model/plot_tweedie_regression_insurance_claims.html#sphx-glr-download-auto-examples-linear-model-plot-tweedie-regression-insurance-claims-py)
- [https://github.com/scikit-learn/scikit-learn/pull/9405](https://github.com/scikit-learn/scikit-learn/pull/9405)
- [https://github.com/scikit-learn/scikit-learn/issues/5975](https://github.com/scikit-learn/scikit-learn/issues/5975)

### GLM with h2o

- They already have implemented for Python and R the whole GLM framework including cross-validation, etc. 
- The problem is that h2o cannot be installed in a corporate laptop due to the company firewall.
- Another issue is that you are forced to do the data management using h2o tools. It seems you cannot use pandas or matplotlib for example.
- Another issue is that at least until the version 3.7 you cannot use conda virtual environments with h2o.

References:

- [About the virtual environments](https://learning.oreilly.com/library/view/practical-machine-learning/9781491964590/ch01.html#idm140586274931888)

### GLM with StatsModels

- All distributions are implemented
- But it seems quite difficult to use scikit-learn's components to apply for example cross-validation.
- It seems that you can predict with StatsModels
- But definitely it is not a modern library like TF for example 

### GLM with TF, Keras or even with PyTorch

For TF you can see [this](https://www.tensorflow.org/tutorials/representation/linear). Of course you can use keras, cross-validation, etc. Someone said on the Gitlab conversation for scikit learn glm models, that nowadays it is easir to iplment all those exotic models (GLM) using TF or PyTorch instead of scikit-learn. Also, on the oreilly media podcast of today they mention that scikit-learn is litter older already…so it seems that I need to devote more time to learn about TF and Pytorch instead due to you can do everything there.

References:

- [https://www.tensorflow.org/probability/api_docs/python/tfp/glm/GammaExp](https://www.tensorflow.org/probability/api_docs/python/tfp/glm/GammaExp)
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTMwMDgwMzk2NF19
-->