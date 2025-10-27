# Resources Consulted

This beginner’s workshop is modeled after many of the freely available workshops that use this “toy” dataset, as well as the official [scikit-learn documentation for the digits dataset](https://scikit-learn.org/1.5/auto_examples/datasets/plot_digits_last_image.html) and the many freely available tutorials about training machine learning models using logistic regression (see the [scikit-learn documentation on this topic](https://scikit-learn.org/stable/auto_examples/linear_model/plot_sparse_logistic_regression_mnist.html), for example).

For a more detailed technical explanation, please see the [GitHub README file](https://github.com/evndttr/d_commonplace/blob/main/README.md).

To create the final two exercises of this workshop, I relied heavily on the [Jupyter Widgets framework (ipywidgets library)](https://ipywidgets.readthedocs.io/en/latest/index.html#learning-widgets) to create interactive buttons and grids. I started this workshop with little familiarity with these tools, so the documentation, tutorial videos, and example notebooks available on the [ipywidgets documentation page](https://ipywidgets.readthedocs.io/en/latest/), as well as numerous freely available online tutorials and videos, were invaluable as I experimented with these interactive tools.

The intention of these widgets, and the code being set to hidden by default, is not to obfuscate the code or the mechanics, but rather to make the projects less intimidating to students who have not had experience writing code. This notebook, intended as a beginner’s activity, would lead into workshops where students write their own code based on provided examples.

On a technical level, the final two exercises are centered around the [gridbox](https://ipywidgets.readthedocs.io/en/7.x/examples/Layout%20Templates.html) and [button](https://ipywidgets.readthedocs.io/en/latest/examples/Widget%20Events.html) widgets.

Exercise five dynamically accepts user input for an array of features (pixel coordinates) that are flattened from a two-dimensional sequence to a single vector, which is then passed to the logistic regression training function. The training, as well as the reset, are set up as functions activated when students press the respective buttons.

Exercise six—which is still a work in progress—is not an example of machine learning, but a simplified rule-based classification system meant to help students understand what a model does during the training process. Like exercise five, the grid matrix again dynamically accepts user input to create an array of pixel coordinates. But this array functions as a sort of “if” condition—a threshold that evaluates each image and returns either True or False depending on whether the image meets that condition.
