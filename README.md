# homebridge Daikin Cloud plugin

This Homebrige plugin connects to the Daikin Cloud and loads all your devices.

The plugin supports some very basic airco manipulations:
- Current room temperature
- Set airco to cooling, heating or auto + the required temperature

## Install

Install from NPM: https://www.npmjs.com/package/homebridge-daikin-cloud

## Config

Add config object to the platform array in your Homebridge `config.json`.

```
{
    "bridge": {
        ...
    },
    "accessories": [],
    "platforms": [
        {
            "username": "<username>",
            "password": "<password>",
            "platform": "DaikinCloud"
        }
    ]
}
```

## Tested with devices

- BRP069C4x
- BRP069A8x

## Credits

Credits for the Daikin Cloud API goes to @Apollon77 for https://github.com/Apollon77/daikin-controller-cloud