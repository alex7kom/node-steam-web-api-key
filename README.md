# Steam Web API Key

Automatically registers and retrieves Steam API key.

__Note__: By using this library you automatically agree to [Steam API Terms of Use](https://steamcommunity.com/dev/apiterms)

## Installation

```
npm install steam-web-api-key
```

## Usage

Require it...

```js
var getSteamAPIKey = require('steam-web-api-key');
```

...then call:

```js
getSteamAPIKey({ sessionID: sessionID, webCookie: cookies }, callback);
```

The second argument to callback will be your API key.

## License

MIT
