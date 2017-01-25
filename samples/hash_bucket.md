## Reference:
[liusida hashbucket](https://liusida.github.io/2016/10/30/hash-bucket/)

### 1. Hash bucket    
```python    
import pandas as pd

data = {'state': ['Ohio', 'Ohio', 'Ohio', 'Nevada', 'Nevada'],
        'year': [2000, 2001, 2002, 2001, 2002],
        'pop': [1.5, 1.7, 3.6, 2.4, 2.9]}

data = pd.DataFrame(data)
print(pd.get_dummies(data, columns=['state','year']))
```

### 2. Pandas dummies    
```python
import pandas as pd

data = {'state': ['Ohio', 'Ohio', 'Ohio', 'Nevada', 'Nevada'],
        'year': [2000, 2001, 2002, 2001, 2002],
        'pop': [1.5, 1.7, 3.6, 2.4, 2.9]}

data = pd.DataFrame(data)
print(pd.get_dummies(data, columns=['state','year']))
``` 
