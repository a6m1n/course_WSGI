
Примеры запуска:
===============

```sh
. .env/bin/activate
python testrun.py
```

```sh
gunicorn main:app.wsgi_app
```

```sh
uwsgi --ini uwsgi.ini
```

```sh
links:
./
./new_url
./<short_id>/details
./all_links
./login
````
