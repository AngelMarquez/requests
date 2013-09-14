Requests: HTTP for Humans
=========================

Requests is an Apache2 Licensed HTTP library, written in Python, for human
beings.


This fork adds the latest urllib3 to allow for improved http proxy support in certain 
situations you might encounter in an enterprise environment. If you ever found your way
to https://github.com/shazow/urllib3/pull/170 then this fork is for you.

Issues this fork tries to fix
-----------------------------

* Using SSL certificates to authenticate with a server via a proxy
* Using SSL certificates to authenticate with a server via a proxy with Basic Authentication
* Using SSL certificates to authenticate with a server via a proxy with NTLM Authentication
