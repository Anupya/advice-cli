# advice-cli
A simple Command Line Interface (CLI) to give you random advice about stuff.

[![HitCount](http://hits.dwyl.com/Anupya/advice-cli.svg)](http://hits.dwyl.com/Anupya/advice-cli) ![](https://img.badgesize.io/Anupya/advice-cli/master/advice.svg) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/issues) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

![](https://raw.githubusercontent.com/Anupya/advice-cli/blob/master/screenshot.png)

All data is from [adviceslip](https://api.adviceslip.com/).

## Installation

First, install jq which is a command line json parser using this command:

### Mac
```
brew install jq
```

### Windows
```
chocolatey install jq
```

### Linux
```
sudo apt-get install jq
```

Find more information about installing jq [here](https://stedolan.github.io/jq/download/).    

Second, run the following command in your terminal:

```
curl "https://raw.githubusercontent.com/Anupya/advice-cli/master/advice" -o /usr/local/bin/advice && chmod +x /usr/local/bin/advice
```

## Usage

You are all set! Enter this in your terminal to receive a new dad joke :)

```
advice
```

## Development

```
git clone https://github.com/Anupya/advice-cli.git
cd advice-cli
vim advice
```

## License

MIT License

