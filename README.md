# Chordsite
A demo project for [ChordGenerator](https://www.pkmurphy.com.au/chordgenerator/)

## Installation

Firstly, please have Python 3 installed. That is the most important requirement.

The next thing to do is get a virtual environment happening
[as explained here](https://docs.python.org/3/library/venv.html). So choose a
directory where you want the stuff on your machine (such as `projects`) and run
these commands to create and activate the virtual environment.

```
python3 -m venv chordsitedemo
cd chordsitedemo
source bin/activate
```

Then you can get the source from github like this:

```
git clone https://github.com/peterkmurphy/chordsite.git
cd chordsite
```

There's a requirements.txt file which has all the dependencies:

```
pip install -r requirements.txt
```

Then create an `.env` file in the same directory as the `settings.py` file.
This should have the format

```
SECRET_KEY=what_you_secret_key_is
```

And then you run the server as:

```
python manage.py runserver
```

(C) Peter Murphy, 2022.
