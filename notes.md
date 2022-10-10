## Using [Scikit Learn](https://scikit-learn.org/stable/user_guide.html) for ML 

### Generally the same as other ML libraries
- For instance to instantiate a model, import the _'estimator object'_ and assign it to the variable you want.. usually you'll see this as 'model'

```
import numpy as np
from sklearn.linear_model import LinearRegression
from sklearn.cross_validation import train_test_split


model = LinearRegression(copy_X=True, fit_intercept=True, nomralize=True)

X, y = np.arrage(10).reshape((5,2)), range(5)
print(X)
## array([[0,1],
          [2,3],
          [4,5],
          [6,7],
          [8,9]])
print(list(y))
## [0, 1, 2, 3, 4]
```

- Scikit will split your data for you

- Makes training very simple.

### Selecting Algorithm 

![](scikit_algo_selection_map.png)