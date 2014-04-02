# Hubot Lingr Adapter

This is the [Lingr](http://lingr.com) adapter for Hubot that allows you to interact with the Lingr bots.

![](http://dl.dropbox.com/u/135035/Screenshots/1kbwtcjnfma5.png)

## Installation

* Add `hubot-lingr` as a dependency in `package.json`
* Install dependencies with `npm install`
* Run hubot with `bin/hubot -a lingr` (in `Procfile` if you run on Heroku)

## Usage

### Configuration

You need the following environment variables to configure hubot:

* `HUBOT_LINGR_BOT`: Bot id of your Lingr bot
* `HUBOT_LINGR_SECRET`: Secret Key of your Lingr bot
* `HUBOT_LINGR_ENDPOINT`: (Optional) API path to serve Hubot commands. Defaults to `/hubot/lingr`

### Bot Settings

Once you run hubot with the configuration above, you should set `http://you.example.com/hubot/lingr` as a callback URL on Lingr bot configuration screen.

![](http://dl.dropbox.com/u/135035/Screenshots/sye6qpfwqh9_.png)

## License

MIT License

## Copyright

Tatsuhiko Miyagawa, 2014
