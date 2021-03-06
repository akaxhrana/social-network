# THE COUNTRYMEN

Social networking revolves allows like-minded individuals to be in touch with each other using websites and web-based applications. Facebook, Myspace, Twitter, and LinkedIn are examples of social networking sites. The definition of the term “social network” is still very loose, as it is still a relatively new technology that’s subject to rapid changes.

## Installation

### Build from Source

Clone the repository and checkout to stable commit

```
git clone https://github.com/akaxhrana/social-network.git
cd social-network
```

## Install Requirements

You need Python3 to run this  

For Linux:
```
sudo apt install python3
```

Install dependencies with:
```
pip install -r requirements.txt
```
or 
```
python3 -m pip install r -requirements.txt
```

## Usage

Change directory to `./social-network/` folder with

```
cd social-network
```

Run server with:

```
python3 manage.py runserver
```

Server will start at localhost:8000

Simply open:
```
http://127.0.0.1:8000/
```


## Admin Panel
Open admin panel at :
```
http://127.0.0.1:8000/admin
```

## References

- [https://docs.djangoproject.com/en/3.2/](https://docs.djangoproject.com/en/3.2/)
- [MDN Docs](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Introduction)
