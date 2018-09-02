# Flask App
A Flask application template.

## Requirements

### Python
[Python Download Page](https://www.python.org/downloads/)

### Pip
[Pip Download Page](https://pip.pypa.io/en/stable/installing/)

### Virtualenv (If Using Python 2.*)
[Virtualenv Download Page](https://virtualenv.pypa.io/en/stable/installation/)



## Installation

### Clone
```
git clone https://github.com/matthewstewart/flask-app.git
cd flask-app
```

### Create Virtual Environment

#### Python 2.*
```
virtualenv venv
```

#### Python 3.*
```
python3 -m venv venv
```


### Activate Virtual Instance

#### Linux/Unix
```
source venv/bin/activate
```

#### Windows
```
venv\Scripts\activate
```

### Install Dependencies
```
pip install -r requirements.txt
```

### Run Application
```
flask run
```


### Flask CLI

#### Create Database Migration Repository
```
flask db init
```

#### Create Database Migration
```
flask db migrate -m "my migration message"
```

#### Run Database Migration/s
```
flask db upgrade
```

#### Undo Last Database Migration
```
flask db downgrade
```

#### Run Flask Shell
```
flask shell
```

#### Run Application
```
flask run
```

### Dependencies

#### View Dependencies
```
pip freeze
```

#### Add Dependency To requirements.txt
From the root directory:
```
pip freeze > requirements.txt
```

### Install Dependencies
From the root directory:
```
pip install -r requirements.txt
```
