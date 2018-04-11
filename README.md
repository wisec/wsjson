# WSJSON 
wsjson is a slight modification of wscat https://github.com/websockets/wscat to deal with
JSON in multiple lines.

```
$ wsjson -c ws://echo.websocket.org 
connected (press CTRL+C to quit)
> {"test":2
}
> {"result":"ok"}

```

## License

MIT
