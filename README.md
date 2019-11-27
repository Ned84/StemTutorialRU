# StemTutorialRU

## A few changes for the Stem Tutorial "From Russia with love" for python 3.8.

Added certifi and changed the output.

```
 query.setopt(pycurl.CAINFO, certifi.where())
 ```

The Output is not filtered but should read that Tor is used and the specific IP (in this case Russia).

```
Congratulations. This browser is configured to use Tor.
Your IP address appears to be:  ***.***.***.***
``` 

Install certifi:
```
python -m pip install certifi
```

Install pycurl:
``` 
python -m pip install pycurl
```
