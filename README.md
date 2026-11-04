# TAMP

<picture>![GitHub repo size](https://img.shields.io/github/repo-size/sekedus/tamp?label=Size)</picture>
[![GitHub License](https://img.shields.io/github/license/sekedus/tamp?label=License)](https://github.com/sekedus/tamp/blob/main/LICENSE)
[![Badge DeepWiki]](https://deepwiki.com/sekedus/tamp)

TAMP (Termux, Apache, MariaDB, PHP)

TAMP is a local http web server for Android using Termux, with installation packages: Apache, MySQL/MariaDB, PHP, phpMyAdmin, & Composer.

ㅤ
## Requirements

- [Termux](https://github.com/termux/termux-app/releases/latest) **v0.118.0** or higher
- Stable and fast internet connection

ㅤ
## Installation

1. Install & open Termux
2. Update & upgrade packages: 
```bash
pkg update && pkg upgrade
```
3. Grant Termux storage permission: 
```bash
termux-setup-storage
```
4. Install `git` & clone this repo: 
```bash
pkg install git -y && cd ~/ && git clone https://github.com/sekedus/tamp.git
```
5. Install TAMP: 
```bash
cd ~/tamp && bash setup && cd ~/
```
6. Wait until installation is complete.
7. Enjoy!

ㅤ
## Usage

- Run `tamp start` to open url in browser.
- Local web server with SSL:
  * run: `tamp start-ssl`
  * port: `8443`
  * url: `https://localhost:8443`
- Login phpMyAdmin:
  * url: `http://localhost:8080/phpmyadmin`
  * username: `root`
  * password: {leave_it_blank}
- **htdocs** folder can be found in:
  * `/sdcard/htdocs`
  * or `/storage/emulated/0/htdocs`

ㅤ
## Commands

- tamp start
- tamp start-ssl
- tamp stop
- tamp update
- tamp uninstall

ㅤ
## Credits

- [Termux](https://github.com/termux/termux-app)
- [parzibyte.me](https://parzibyte.me/blog/en/2019/04/28/install-apache-php-7-android-termux/)
- [termux-php-apache2-setup](https://github.com/gungunpriatna/termux-php-apache2-setup)
- [termux-webserver](https://github.com/HadiKhoirudin/termux-webserver)

ㅤ
## License

TAMP is licensed under the GNU General Public License v3.0. See the [LICENSE](https://github.com/sekedus/tamp/blob/main/LICENSE) file for more details.


<!-- Badges -->
[Badge DeepWiki]: https://img.shields.io/badge/Ask%20DeepWiki-blue.svg?labelColor=000000&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAAACXBIWXMAAAPoAAAD6AG1e1JrAAACIUlEQVRYw+2XP2gUQRTGv7d3JhYWQawkIBaCVWzETos0gmAnVoKNTSoLK0E7EQQrC20sBVFBtLPQRgTBtBaKjYgIQUSxiJq7fT+LvCGPJZdNLt4dQj5Y3u7sznzfzLw/s9IO/icANiniCujEfWdsQgBLxAbsbraPZcmBfcAt4DNwKQsZNfEUsAB8YRV12LfA6ZHuedg7AO7ed/c+UBcbQhbiu+6wXIM6EnZWkszMJe2Ke0n6I2la0v51hFeSMLN6OwIK6jJwEBdUYb2MAxRSz6sY4geiahFgLe1Hwq6YWe3us8AN4FQQU4QM64SPY69Xyr43fADgNjAPXHb3peSsD4FDQ0VLEjAHvIhBPS6AHvA1bBO9JPAXcHFbIRtJ5yzwIQZ9CZwAusDJENIkLqsG8DpNyIZJwSUk9wLHgakcesC1JCCjiHm1kYDNOEjptCxpSVK/8f73OFLxPLAYM3oCzEX7MXf/lJbc/8kWpA4HgQdpYI9IWAbeh83whi84cHXL+58EPBoQhnmm94EzwE3gZ2p/Dhzdbhg+TaRr01x7ftb4/jBwFzjXrCvDpmLW9crVLNeR9CaapoGemb2TdCERW1tNaBNQ8jktwmozqwtpqRNtdWAjARYk39IS12ZWRX7vmJmA71nQZgi36gN7gCvAj5xc3P0jcH7kx7Ik5IC73wsh14GZsZySow5002l4Jr0b6+m4eSyvpAn8lEzsx2QHo8RfUrlN+uPq4ksAAAAASUVORK5CYII=
