double
======

A simple command to execute a background process behind a foreground process.
The background process will be terminated when the foreground process finished.

Usage
-----

```
double -b "Background Command" Foreground-Command [args...]
```

e.g.

```
double -b "vmstat 1 > vmstat.log" sleep 5
```

Supported Environment
---------------------

* Linux
