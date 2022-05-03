# Link any Python file to Django and use

### Folder Structure

.
├── core
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py   --> Django Settings
│   ├── urls.py
│   └── wsgi.py
│
├── any.py   --> Any Python File
└── manage.py


### First Open any.py 
```
import os
os.environ.setdefault("DJANGO_SETTINGS_MODULE", "core.settings")

import django
django.setup()

...

You can use any model you want :)

```


