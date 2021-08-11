# pywebscan.py

A simple threaded web scanner written in Python using urllib3 and ThreadPoolExecutor. It takes a host (single or list) argument, plus a path list, and returns request results matching a defined set of status codes (ie. found resources via HTTP 200). 

## usage

`pywebscan.py [https://example.com | 192.168.1.1 | hosts.txt] paths.txt`
