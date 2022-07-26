**ffplayout-api**
================

ffplayout-api (ffpapi) is a non strict REST API for ffplayout. It makes it possible to control the engine, read and manipulate the config, save playlist, etc.

To be able to use the API it is necessary to initialize the settings database first. To do that, run:

```BASH
ffpapi -i
```

Then add an admin user:

```BASH
ffpapi -u <USERNAME> -p <PASSWORD> -m <MAIL ADDRESS>
```

Then run the API thru the systemd service, or like:

```BASH
ffpapi -l 127.0.0.1:8787
```

**For possible endpoints read: [api endpoints](https://github.com/ffplayout/ffplayout/blob/master/docs/api.md)**

ffpapi can also serve the browser based frontend, just run in your browser `127.0.0.1:8787`.
