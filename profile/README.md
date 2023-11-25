## VSCUBING 

How to run dev server:
```
$ cd vscubing-frontend; bun run dev
$ cd vscubing-backend; source venv/bin/activate; python3 manage.py runserver
$ cd alg.cubing.net; live-server src/alg.cubing.net --no-browser
$ cd cstimer; make; php -S 127.0.0.1:8081 -t dist
```
note: don't run cstimer from the src/, always make and run from dist/, src is instable
