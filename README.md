# WSJSON 
wsjson is a slight modification of wscat https://github.com/websockets/wscat to deal with
JSON in multiple lines.

# Install
```
git clone git@github.com:wisec/wsjson.git
cd wsjson
npm install
bin/wsjson -h
```
# Usage
Same as wscat:
```
$ wsjson -c ws://echo.websocket.org 
connected (press CTRL+C to quit)
> {
 "test":2
}
> {"result":"ok"}

```

## License

MIT
