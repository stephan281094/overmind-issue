# Overmind issue

After starting the dev server and opening the DevTools, the following error can
be seen:

```
WebSocket connection to 'ws://localhost:3031/?name=Overmind%20issue' failed:
Error in connection establishment: net::ERR_CONNECTION_REFUSED
```

## How to reproduce

- `$ git clone git@github.com:stephan281094/overmind-issue.git`.
- `$ yarn # or npm install`.
- `$ yarn dev # or npm run dev`.
- `$ open http://localhost:1234`.
- Open DevTools and notice the error.
