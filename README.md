# fasttrig



A fast and lightweight approximation of sin, cos, and tan using 4th-degree polynomials.

Unit: radian

Accuracy: Error < 0.001

If Numba is available fasttrig will use it.


## Example

```python
import numpy as np
from fasttrig import P1_fast, fast_cos, fast_tan

print(P1_fast(np.pi))         
print(P1_fast([0, np.pi/2, np.pi])) 
print(fast_cos([0, np.pi/2, np.pi]))
print(fast_tan(np.linspace(0, 2*np.pi, 100)))

```


Fast approximation of sin, cos, tan using forth degree polynomials


A fast and lightweight approximation of sin, cos, and tan using 4th-degree polynomials.

Accuracy: Error < 0.001


