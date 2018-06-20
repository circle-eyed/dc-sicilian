# DC-Sicilian

Currentyly this project contains the following services on the server side:

* Shadowsocks
* Kcptun

and the followling services on the client side:

* Shadowsocks
* Kcptun
* Privoxy

## Server Side

* Shadowsocks server, default on port 8388, and
* Kcptun server provides kcp acceleration for the Shadowsocks server, default on port 29900

## Client Side

* Kcptun client privodes kcp acceleration, working with the same service on the server side, no public port opened, and
* Shadowsocks client provides socks5 proxy directly connected to the server, default on port 1080, and
* Shadowsocks client privodes socks5 proxy connected to kcptun client with kcp acceleration, default on port 1081, and
* Privoxy provides http proxy with Shadowsocks client, default on port 8118, and 
* Privoxy provides http proxy with Shadowsocks client with kcp acceleration, default on port 8119

