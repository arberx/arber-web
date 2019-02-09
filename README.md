# arber-web
Current Website! : https://www.arberx.com/

Super Simple Website made with Python-Flask. Utilizes flask-bootstrap (mobile optimized), particles.js running on an nginx server.  

SSL layer added with https://letsencrypt.org/!

## Setup
**Assumes using python3.6 and node 6.5+**

### Setup env's
```shellsession
$ python3.6 -m venv env
$ source env/bin/activate
$ pip3.6 install nodeenv
$ nodeenv --python-virtualenv
$ source env/bin/activate
```

### Install Dependencies
```make install```

### Run
``` make run```

App will be running on localhost:8000

