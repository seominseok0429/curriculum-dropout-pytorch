# curriculum-dropout-pytorch

curriculum dropout implementation with pytorch

```python

def curriculum_p(p, epoch):
    gamma = 0.0001
    return (1-(1.-p) * np.exp(-gamma*epoch) + p)

```
