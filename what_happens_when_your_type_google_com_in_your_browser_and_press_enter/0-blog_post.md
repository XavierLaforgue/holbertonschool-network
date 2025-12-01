# What happens when you type [https://www.google.com](https://www.google.com) in your browser and press `Enter` ?

## Requirements the post should cover:

- [ ] DNS request
- [ ] TCP/IP
- [ ] Firewall
- [ ] HTTPS/SSL
- [ ] Load-balancer
- [ ] Web server
- [ ] Application server
- [ ] Database

## 0. Initial typing
When typing into the address bar of the browser, the browser will search in the history and cacheif for URLs that start with or contain those characters and propose autocompletion of the address from the found results.

## 1. URL recognition
With the input string in the address bar, the browser checks if it is a url or not.
If it is not a url it will send the string to the search engine.
If it is a url it will attempt to resolve it.

## 2. Protocol
As the web protocol to be used is provided in the url, the browser will know the port it needs to connect to (this being 443 for the https protocol).

## 3. DSN request
## X. TCP/IP

## References
[What happens when you type google.com into your browser and press enter? (Detailed Analysis)](https://www.youtube.com/watch?v=dh406O2v_1c)
