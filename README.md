# YBurbs website
Simple website to fiddling and testing.

## Run it
You can just drop *default.html* into a Chrome browser window. If you run 
into cross-origin request errors, use Python to run a local HTTP server and 
access it from the browser.

Run Python simple HTTP server from root of project directory:

(Linux/Mac)
```shell
python -m SimpleHTTPServer 8888
```
(Windows)
```shell
python -m http.server 8888
```

Access the page in a browser at http://localhost:8888/default.html
