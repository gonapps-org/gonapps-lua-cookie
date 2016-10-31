gonapps-cookie-decoder
=

## About
Cookie for lua
## Usage
**installation**
```bash
$ sudo luarocks install gonapps-cookie
```
**example code**
```lua
local cookieModule = require "gonapps.cookie"
local cookie = cookieModule.new("aaaaaaaaaaaa=bbbbbbbbbbbb; HttpOnly")
if cookie.flags["HttpOnly"] then
print(cookie.toString())
```
## License
LGPLv3
