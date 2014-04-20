docker-miniircd
===============

A quick way to get a simple IRC server for testing.

How to get it
-------------

Download it using the trusted docker repository:

```
docker pull dermitch/docker-miniircd
```

Build it yourself
-----------------

```
git clone https://github.com/DerMitch/docker-miniircd.git
cd docker-miniircd
docker build -t miniircd .
```

Use it
-----

```
docker run -i -t -p 6667:6667 dermitch/miniircd
```

Please note that debugging is enabled by default. If you don't need it, remove
the options from the Dockerfile.

Have fun!
