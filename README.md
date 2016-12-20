# Pi Feeder

Welcome, this is the code for my WIP Raspberry Pi powered pet feeder.

### Dependencies

Install dependencies using `pip`, preferably `pip3` since this server needs to be run with Python 3.

* Flask
* sqlite3
* gpiozero
* bcrypt
* tzlocal
* dateutil
* time_uuid

### Running

To run the server:

```bash
$ python server.py
```

If `python` won't impliclty use `python3`, you should run it with `python3 server.py`.

This will run the HTTP server, create an admin account, and do any other required initial setup.