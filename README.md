
# .net-runtimeconfig

Need For Dash.tatsi.eu do run .net server

change the name of <Name>.runtimeconfig.json to <yourfilewithoutfileending>.runtimeconfig.json

and paste you config 

example for .net core 3.1:


## Example for .net core 3.1

```
{
  "runtimeOptions": {
    "tfm": "netcoreapp3.1",
    "framework": {
      "name": "Microsoft.NETCore.App",
      "version": "3.1.0"
    },
    "configProperties": {
      "System.Globalization.UseNls": true,
      "System.Net.DisableIPv6": true,
      "System.GC.Concurrent": false,
      "System.Threading.ThreadPool.MinThreads": 4,
      "System.Threading.ThreadPool.MaxThreads": 25
    }
  }
}
```

