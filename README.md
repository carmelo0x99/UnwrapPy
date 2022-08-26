# UnwrapPy
Python script decoding shortened URLs and displaying such "hidden" info as the source IP address.

The script is based on [Requests](https://requests.readthedocs.io/) and the [IPinfo Python Client Library](https://github.com/ipinfo/python).
The two libraries are used to safely decode short URLs and gather additional info such as the source IP address, location and more.

### Initialize
```
python3 -m venv .
source bin/activate
(UnwrapPy) python3 -m pip install --upgrade pip setuptools wheel
(UnwrapPy) python3 -m pip install requests ipinfo
```

