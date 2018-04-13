# WeatherAdvisor

## Objective:

Provides a brief, near-term weather forecast to a user in his current location

## Outline of approach: 

 1. Identify a (free) online source of weather data and forecasts, and code the logic for extracting and summarizing that data into a brief message. 
 
 2. Identify a (free) online service to generate and broadcast messages containing brief weather forecasts. Some candidates: 
 
 * SMS - twilio and Amazon's AWS are candidates; others will be evaluated. 
 * Twitter - a potentially simpler system: users 'subscribe' to a Twitter feed, and get periodic updates to weather for a specified location. Has its drawbacks, and not general purpose, but may be simpler to develop initially? 

## Resources:

* [Weather data; the Dark Sky API](https://darksky.net/dev/docs)

* [twilio SMS](https://www.twilio.com/sms/pricing/gb) 

* [twilio YouTube video demo of API](https://www.youtube.com/watch?v=knxlmCVFAZI) 

* [Amazon's SNS solution for messaging is attractive because AWS offers much more than SMS](https://aws.amazon.com/sns/?ft=n)

* [An AWS sample on github](https://github.com/aws-samples/aws-iot-elf) 

* [The Python SDK for AWS](https://aws.amazon.com/sdk-for-python/)

* [A How-To for an IM service called "Telegram"](https://maker.pro/education/how-to-use-telegram-instant-messaging-on-raspberry-pi)

* [Some scuttlebut on "Telegram"](https://www.theregister.co.uk/2018/04/09/russian_regulator_asks_courts_to_disconnect_telegram/) 

* [The Telegram website](https://telegram.org/)

* [A Wikipedia article on Telegram](https://en.wikipedia.org/wiki/Telegram_(service)) 

* [More buzz on Telegram + references to competitors](https://www.theverge.com/2014/2/25/5445864/telegram-messenger-hottest-app-in-the-world) 

* [The Telegram API](https://core.telegram.org/bots/api)

* [Telegram API Terms of Service (it's FREE!)](https://core.telegram.org/api/terms)

* [Build an SMS Terminal using Wammu/Gammu and a GSM module](https://wammu.eu/)

