# SAP BusinessObject audit log extractor

```console
Usage:
    boaex
    boaex [--uid=USERID --pwd=PASSWORD --host=HOST --dbn=DATABASE --loop=LOOP --batch=BATCH --log=LEVEL]
    boaex [-u USERID -p PASSWORD -h HOST -d DATABASE -l LOOP]
    boaex --help
    boaex --version

Options:
    -u USERID --uid=USERID  User name [default: dba].
    -p PASSWORD --pwd=PASSWORD  Password [default: ].
    -h HOST --host=HOST  Server host name [default: localhost].
    -d DATABASE --dbn=DATABASE  Database name [default: BI4_Audit].
    -l LOOP --loop=LOOP  Looping interval in seconds, max 3600 [default: 0].
    --batch=BATCH  Batch record count, [default: 100].
    --log=LEVEL  Log level DEBUG, INFO, WARNING, ERROR [default: WARNING].
    --help  Show this screen.
    --version  Show version.
```

Alternatively, you can specify the same options in the environment variables
BOAEX_USERID, BOAEX_PASSWORD, BOAEX_HOST, BOAEX_DATABASE, BOAEX_LOOP, BOAEX_LEVEL
Recommended for daemon password handling
