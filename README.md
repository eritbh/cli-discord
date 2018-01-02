# discord-cli

A Discord command line interface that allows you to log in as your bot. Built in Node with [Blessed](https://github.com/chjj/blessed) and [Eris](https://github.com/abalabahaha/eris).

## Usage

```bash
$ git clone https://github.com/Geo1088/cli-discord.git
$ cd cli-discord
$ cp config_sample.json config.json
$ # Fill out config.json
$ yarn # or npm install
$ yarn start # or npm start
```

## Interface controls

- `g`: Focus guilds list
- `c`: Focus channels list
  - `enter` or `space` while in the channels list: Switch to the selected channel
- `m`: Focus messages area
  - `escape`: Scroll to the bottom of the view
- `up` or `k`: Scroll up in the selected view
- `down` or `j`: Scroll down in the selected view
- `C-q`: Exit the client
