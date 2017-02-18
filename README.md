# useful-bluemix-commands
A collection of useful/helpful commands for Bluemix

----

Get a log trace of the app's logs
```bash
CF_TRACE=true cf logs myBluemixApp
```

Save a log trace of the app's logs
```bash
CF_TRACE=myBluemixApp.log cf logs myBluemixApp
```

Get a log trace of the app while pushing
```bash
CF_TRACE=true cf push myBluemixApp
```
