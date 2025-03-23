# Fasttrig



A fast and lightweight approximation of sin, cos, and tan using 4th-degree polynomials.

Unit: radian

Accuracy: Error < 0.001

By testing 10^9 data points(With numba), the efficiency is 200% of np.sin

If Numba is available fasttrig will use it. (Ensure the version is compatible with numba)


## Example

```python
import numpy as np
from fasttrig import P1_fast, fast_cos, fast_tan

print(P1_fast(np.pi))         
print(P1_fast([0, np.pi/2, np.pi])) 
print(fast_cos([0, np.pi/2, np.pi]))
print(fast_tan(np.linspace(0, 2*np.pi, 100)))

```





