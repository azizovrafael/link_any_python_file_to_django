# Link any Python file to Django and use

### Folder Structure
<br>
.<br>
├── core<br>
│   ├── __init__.py<br>
│   ├── asgi.py<br>
│   ├── settings.py   --> Django Settings<br>
│   ├── urls.py<br>
│   └── wsgi.py<br>
│<br>
├── any.py   --> Any Python File<br>
└── manage.py<br>

### First Open any.py 
```
import os
os.environ.setdefault("DJANGO_SETTINGS_MODULE", "core.settings")

import django
django.setup()

...

You can use any model you want :)

```


