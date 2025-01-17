[![styled with prettier](https://img.shields.io/badge/styled_with-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#)

# WSPR
WebSocket proxy for post http requests. Perfect for testing purposes/mocks 🚀

![wssExample](https://user-images.githubusercontent.com/2823336/88941927-814ad280-d281-11ea-8624-9637c13ee868.jpg)

### Installation

```
npm i -g wspr
```

### Usage

Just run
```
wspr
```

after, you will see output with 2 urls:
```
WebSocket server started ws://localhost:3005
HTPP proxy server started http://localhost:3006
```

### Broadcast message to clients: 
To broadcast message to clients send a  post requests with a string/json body (via postman or curl) to http enpoint provided
on the previous step.

```
curl -d "{"hello": "world"}" -X POST http://localhost:3006
```

## Enjoy 🚀🥤
