# California Housing Price Prediction with TensorFlow and Keras

## Requirements

To run this code, you need to have the following packages installed:

- Python 3.x
- TensorFlow
- Matplotlib
- Pandas
- NumPy


## Building the Model for One Input & One Output

### Loading Dataset

First, we load the California housing dataset from `sklearn`:

```python
from sklearn.datasets import fetch_california_housing
housing = fetch_california_housing()

