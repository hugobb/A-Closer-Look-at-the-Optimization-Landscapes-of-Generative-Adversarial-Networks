# A-Closer-Look-at-the-Optimization-Landscapes-of-Generative-Adversarial-Networks

We provide a conda environment to run the code:
`conda create -f mnist-exp_environment.yml`

The code for computing the eigenvalues and the path-angle is in `plot_path_tools.py`.

To run the code for the Mixture of Gaussian experiment:
`python train_miture_gan.py OUTPUT_PATH --deterministic --saving-stats`

To run the code for the MNIST experiment:
`python train_mnist.py`

The visualization of the results can be done with `mnist_plots.ipynb`
