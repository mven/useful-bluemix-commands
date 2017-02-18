# useful-bluemix-commands
A collection of useful/helpful commands for Bluemix

----

### Log Tracing

Get a log trace of the app's logs
```bash
CF_TRACE=true cf logs myBluemixApp
```

Save a log trace of the app's logs
```bash
CF_TRACE=myBluemixApp.log cf logs myBluemixApp
```

Get a log trace of the app when pushing to Bluemix
```bash
CF_TRACE=true cf push myBluemixApp
```
