Save the current KERNEL 

```python
import dill
dill.dump_session('notebook_env.db') #save the current kernel

import dill
dill.load_session('notebook_env.db') #restored the previusly saved kernel
```