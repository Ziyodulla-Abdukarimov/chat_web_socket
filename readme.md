# Simple Real Time Chat

### -Django
### - Django Channels

### Setup
The first thing to do is to clone the repository:
```sh
git clone https://github.com/Ziyodulla-Abdukarimov/chat_web_socket.git
cd /chat_web_socket
```

Create a virtual environment to install dependencies in and activate it:

```sh
pip install pipenv
pipenv shell
```

Then install the dependencies:
```sh
pip install -r requirments.txt
```
Once `pip` has finished downloading the dependencies:
```sh
python manage.py runserver
```
And navigate to `http://127.0.0.1:8000/`.