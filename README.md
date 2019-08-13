### delorean
---
https://github.com/myusuf3/delorean/

```py
from datetime import datetime
import pytz

est = pytz.timezone('US/Eastern')
d = datetime.now(pytz.utc)
d = est.normalize(d.astimezone(est))
return d

from delorean import Delorean
d = Delorean()
d = d.shift('US/Eastern')
return d
```

```
```

```
```

