# Network Analysis of shorterloop.com

## Request 1

GET /
Status: 200 OK
Type: document

Header:
content-type: text/html

## Request 2

GET main.css
Status: 200 OK
Type: stylesheet

Header:
content-type: text/css

## Request 3

GET app.js
Status: 200 OK
Type: script

Header:
cache-control: public

## DNS Lookup

nslookup shorterloop.com

Output:
76.76.21.21