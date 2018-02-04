# Flyin' In

<p align="center"><img src="LogoFlyinIn.png" width="150px" /></p>

## Welcome
Flyin' In is written in Javascript, JQuery, Bootstrap and uses API's from Twilio, FlightAware, and Google Maps.
This App is UNDER CONSTRUCTION. Please be patient as I am actively developing it and hope to have a working version by mid-February. Thanks.

## Table of Contents
* [Requirements](#requirements)
* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)
* [License](#license)

## Requirements
* Ubuntu (v14.04 LTS)
* NodeJS (v6.12.3)
* Twilio API (with valid Twilio account and token)
  -twilio (v3.11.1)
```
sudo npm install twilio
```
* FlightAware API
  -FlightXML (v2.0)
  -Javascript module, node-rest-client (v3.1.0)
```
npm install node-rest-client
```
* Google Maps
* Javascript
* JQuery (v3.2.1)
* Ajax (v1.12.9)
* HTML5 / CSS
* Bootstrap (v4.0.0)
* Web browser using HTML5
* Semistandard (12.0.0) for Javascript styling

## Installation
Set your computer ENVIRONMENT variables, TWILIO_SID and TWILIO_TOKEN to your values. Don't forget to export them.
In your terminal, git clone the directory with the following command:
```
git clone https://github.com/feliciahsieh/flyinin.git
```

```
$ npm init (and fill out to create your package.json)
```

```
$ npm install twilio
```

## Usage
Use a browser and open index.html. Enter the Airline, Flight Number, and your Phone Number to receive a text message. You will receive information on when you should leave for the airport, depending on your starting location.

Note, text messages will only be sent to phone numbers in your chosen country. To upgrade to international phone numbers, you may need to upgrade your Twilio account.

## Credits
Flyin' In is owned and maintained by Felicia Hsieh ([@feliciahsiehsw](https://twitter.com/feliciahsiehsw)).

## License
Flyin' In is released under the MIT license. See [LICENSE](https://github.com/feliciahsieh/flyinin/blob/master/LICENSE) for details.
