+++
title = 'Trame'
date = 2025-09-02T10:40:09+02:00
draft = true
+++

# ETHERNET-trame


- j'ai décodé la trame sur [site pour décoder trame](https://hpd.gasmi.net/ "site decode trame"):
![apercu](/images/rootme/ethernet-frame-image.png)

- on constate au niveau des données une requête HTTP

```http
 GET / HTTP/1.1\r\n
    Request Method: GET
    Request URI: /
    Request Version: HTTP/1.1
  Authorization: Basic Y29uZmk6ZGVudGlhbA==\r\n
    Credentials: confi:dential
  User-Agent: InsaneBrowser\r\n
  Host: www.myipv6.org\r\n
  Accept: */*\r\n
  \r\n
 Full request URI: http://www.myipv6.org/