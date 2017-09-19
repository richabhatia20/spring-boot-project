# Steps to install Material for MkDocs
* Check Python version
```
$ python --version
Python 2.7.10
```

* Check pip version
```
$ pip --version
-sh: pip: command not found
```

This means no pip found. So we need to add pip manually

If you’re using a Python install on Linux that’s managed by the system package manager (e.g “yum”, “apt-get” etc…), the other option is to download get-pip.py
and run it.  You can use python get-pip.py --prefix=/usr/local/ to install in /usr/local which is designed for locally-installed software

* Downloading the get-pip.py file
```
$ wget https://bootstrap.pypa.io/get-pip.py
$ python get-pip.py --prefix=/usr/local/
```


