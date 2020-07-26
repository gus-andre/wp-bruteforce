# WordPress Bruteforce Admin Login

### Install requirements
```
pip install -r requirements.txt
```

## Features
* 1 Million Wordlist Added
* Standard mode or xml-rpc brute force mode
* http and https protocols supported
* Big wordlist size supported
* Multithreading

### Usage
  * Standard Mode:
```
python wpbrute.py -s [-t TARGET] [-u USERNAME] [-w WORDLIST] [--timeout TIMEOUT VALUE]
```
  * xml-rpc Mode:
```
 python wpbrute.py -x [-t TARGET] [-u USERNAME] [-w WORDLIST] [--timeout TIMEOUT VALUE]
```
