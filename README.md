sauce4zwift-python-client
--------
This is a very basic example of how to use the sauce4zwift WebSocket API for listening
to events.

Sauce for Zwift runs a built-in web server at port 1080 which provides a WebSocket
service as well as a basic JSON REST API (not covered here).

In most cases you can start S4Z and then run this... 

```sh
pip install -r requirements.txt
python ./example.py ws://localhost:1080/api/ws
```

Have a look at the example.py file for more details.  It's pretty self explanatory.
