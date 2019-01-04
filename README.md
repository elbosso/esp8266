# ESP8266 Projects

<!---
[![start with why](https://img.shields.io/badge/start%20with-why%3F-brightgreen.svg?style=flat)](http://www.ted.com/talks/simon_sinek_how_great_leaders_inspire_action)
--->
[![GitHub release](https://img.shields.io/github/release/elbosso/esp8266/all.svg?maxAge=1)](https://GitHub.com/elbosso/esp8266/releases/)
[![GitHub tag](https://img.shields.io/github/tag/elbosso/esp8266.svg)](https://GitHub.com/elbosso/esp8266/tags/)
[![GitHub license](https://img.shields.io/github/license/elbosso/esp8266.svg)](https://github.com/elbosso/esp8266/blob/master/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/elbosso/esp8266.svg)](https://GitHub.com/elbosso/esp8266/issues/)
[![GitHub issues-closed](https://img.shields.io/github/issues-closed/elbosso/esp8266.svg)](https://GitHub.com/elbosso/esp8266/issues?q=is%3Aissue+is%3Aclosed)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/elbosso/esp8266/issues)
[![GitHub contributors](https://img.shields.io/github/contributors/elbosso/esp8266.svg)](https://GitHub.com/elbosso/esp8266/graphs/contributors/)
[![Github All Releases](https://img.shields.io/github/downloads/elbosso/esp8266/total.svg)](https://github.com/elbosso/esp8266)

This repository contains a small number of projects for use with/on the ESP8266 chip, as packaged by the WeMos Mini D1.


## Template Project

The [d1-template](d1-template) project is a skeleton which carries out the basic tasks many projects would require:

* Connects to your local WiFi network.
    * Acting as an access-point if it has not previously connected.
* Refreshes the date/time via NTP.
* Runs a mini webserver.

This project is a good starting point for new work.

## Distance Sensor

The [d1-distance](d1-distance) project is used to determine if my desk-chair
is occupied by measuring a distance with an ultrasonic sensor.

## EPaper Image Display

The [epaper-web-image](epaper-web-image) project demonstrates featching an image over HTTP/HTTPS and drawing
it upon a 4.2" epaper display.

## Helsinki Tram Display

The [d1-helsinki-tram-times](d1-helsinki-tram-times) project shows the departure times of Trams in Helsinki, and is more fully documented [on the project homepage](https://steve.fi/Hardware/helsinki-tram-times/).

## NTP-Based Clock

The [d1-ntp-clock](d1-ntp-clock) does exactly what the name implies, operates as a clock getting the time via NTP.

The project is documented [on the project homepage](https://steve.fi/Hardware/d1-ntp-clock/).


## Pixel Editor

The [d1-pixels](d1-pixels) project presents a simple pixel-editor which can be used to update an 8x8 LED Matrix in real-time, via your browser.

The project is documented [on the project homepage](https://steve.fi/Hardware/d1-pixels/).


## Temperature & Humidity Measurement

This [simple project](d1-temp) records the current temperature & humidity value via a DHT22 sensor, and submits to a local MQ bus.


## Web Radio

The [d1-web-radio](d1-web-radio) project allows a web-browser to control a TEA5767-based radio receiver, allowing you to listen to the radio with ease.

## Water Flow Counting

The [d1-water-meter](d1-water-meter) project is a simple one that measures
the flow of water being sent to our washing-machine.  The data is published
on an MQ bus.
