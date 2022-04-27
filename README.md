# TMKartMode

# Server How-to

1. Place the contents of `Dedicated` folder into your dedicated server's `UserData` folder.
2. Start the server:

Linux:
```bash
./TrackmaniaServer /game_settings=MatchSettings/TMkart.txt /dedicated_cfg=dedicated_cfg.txt
```

Windows:
```powershell
TrackmaniaServer.exe /game_settings=MatchSettings/TMKart.txt /dedicated_cfg=dedicated_cfg.txt
```

## Development

It's easier to work with development when you're setup with symlink to the scripts...

Here's a example how to setup symlink for windows:

```cmd
D:\trackmania\server\UserData> mklink /D Scripts d:\trackmania\TMKartMode\Dedicated\Scripts
```


