# California Housing Price Prediction with TensorFlow and Keras

## Requirements

To run this code, you need to have the following packages installed:

- Python 3.x
- sklearn
- TensorFlow
- Matplotlib
- Pandas
- NumPy

### Loading Dataset

We load the California housing dataset from `sklearn`:

```python
from sklearn.datasets import fetch_california_housing
housing = fetch_california_housing()

