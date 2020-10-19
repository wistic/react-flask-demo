### Installing

While in your preferred terminal;

Clone the repository and open it.

Make and activate a python virtual environment using `virtualenv`

```bash
virtualenv venv

source venv/bin/activate
```

With the virtual environment activated, install the project dependencies for the flask server

```bash
pip3 install -r requirements.txt
```

```bash
cd react-frontend/
```

```bash
yarn install
```

### Serving the application

You can start a local server by running

```bash
cd flask-backend
python3 main.py
```
visit http://127.0.0.1:5000/ to view your application.


References: <a href="https://blog.learningdollars.com/2019/11/29/how-to-serve-a-reactapp-with-a-flask-server/">React-Flask</a>
