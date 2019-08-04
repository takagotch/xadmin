### xadmin
---
https://github.com/sshwsfc/xadmin

```py
// tests/urls.py
from django.conf.urls import patterns, include

urlpatterns = patterns('',
  (r'^view_base/', include('view_base.urls')),
)
```

```sh
pip install xadmin
pip install git+git://github.com/sshwsfc/xadmin.git
pip install git+git://github.com/sshwsfc/xadmin.git@django2

cd domo_app
./manage.py migrate
./manage.py runserver
```

```
```


