# fxserver-esx_optionalneeds
FXServer ESX Optional Needs

[REQUIREMENTS]
- esx_status https://github.com/FXServer-ESX/fxserver-esx_status

[INSTALLATION]

1) CD in your resources/[esx] folder
2) Clone the repository
```
git clone https://github.com/FXServer-ESX/fxserver-esx_optionalneeds esx_optionalneeds
```
3) Add this in your server.cfg :

```
start esx_optionalneeds
```

If you Want to use esx_unicorn job item delete this in server/main.lua

```
--[[(delete me)
```
AND
```
--]]--delete me
```
