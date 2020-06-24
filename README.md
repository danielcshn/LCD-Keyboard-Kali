LCD Keyboard for Kali Linux on Raspberry Pi
=============================

On-Screen Keyboard for TFT LCD & Raspberry Pi & Kali Linux.

Disclaimer: This project is intended for non-commercial educational purposes.

# Install

## STEP 1: Install Gambas3 (required)

```sudo apt-get update```<br>
```sudo apt-get upgrade```<br>
```sudo apt-get install gambas3```<br>

## STEP 2: Download LCD-Keyboard-Kali
- Download the [latest release here](https://github.com/danielcshn/LCD-Keyboard-Kali/releases/latest).
- Installation package file available (.deb).
- Gambas application file available (.gambas).

## STEP 3: Install LCD-Keyboard-Kali

- For the Installation package file available (.deb):
```sudo dpkg -i /path/to/deb/file```<br>

- For the Gambas application file available (.gambas):
```cp LCD-Keyboard-Kali.gambas /usr/bin/```<br>
```cp LCD-Keyboard-Kali.gambas /usr/local/bin/```<br>
```cd /usr/bin/```<br>
```chmod 777 LCD-Keyboard-Kali.gambas```<br>
```cd /usr/local/bin/```<br>
```chmod 777 LCD-Keyboard-Kali.gambas```<br>
```./LCD-Keyboard-Kali.gambas```<br>

# Manual

## Usage

The application is currently designed only to work against one or more open Terminals in the graphical environment of Kali Linux.

## Buttons

- ≡ = Expansion
- ⇧ = Lowercase
- ⬆ = Uppercase
- ❶ = Terminal 1
- ❷ = Terminal 2
- ❸ = Terminal 3
- ❹ = Terminal 4
- ❺ = Terminal 5
- ❻ = Terminal 6
- × = Ctrl+c
- ✕ = Close

# Screenshots

## Minimalist
![Screenshot](https://github.com/danielcshn/LCD-Keyboard-Kali/blob/master/img/1.jpg)
## Expanded
![Screenshot](https://github.com/danielcshn/LCD-Keyboard-Kali/blob/master/img/2.jpg)

# Changelog

## v1.0.1-20200623
- First version

# Last test

## v1.0.1-20200623
- Kali Linux RaspberryPi 2 (v1.2), 3 and 4 (64-Bit) - v2020.2b
- Raspberry Pi 3 Model B v1.2
- 3.5inch RPi Display
- LCD-Keyboard-Kali-v1.0.1

It works perfectly!

# Links and References
- https://github.com/danielcshn/LCD-show-kali
- https://github.com/goodtft/LCD-show
- http://www.lcdwiki.com/RaspberryPi-LCD-Driver
