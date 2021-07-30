This is an example project of retrieving data from [twelvedata](https://twelvedata.com/) and using [Monument](https://monument.ai/) to predict stock returns.

### Overview

In this project, we predict the **weekly** return for the Amazon stock `AMZN` **one week ahead**, by using the Gaussian Process-integrated LightGBM algorithm (`G-Boost`). We use historical prices and a few technical indicators as independent variables. To evaluate model performance, we use **directional accuracy** as the metric, where we achieved 56% in validation and 57% in serving.

For more details, please read `mai_twelvedata_project.ipynb`.

### Developing Environment

* Python 3.9.2

    * pandas 1.2.3

    * requests 2.25.1

* Monument.app 1.4.13

    * monument (python package) 0.0.1

### Further Reading

* Monument quickstart: [https://monument.ai/m/quick-start](https://monument.ai/m/quick-start)

* Monument Python package: [https://pypi.org/project/monument](https://pypi.org/project/monument)

* twelvedata documentation: [https://twelvedata.com/docs#getting-started](https://twelvedata.com/docs#getting-started)

* getting twelvedata API key: [https://twelvedata.com/register](https://twelvedata.com/register)
