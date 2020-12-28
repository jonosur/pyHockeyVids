# pyHockeyVids

[![Language](https://img.shields.io/badge/language-Python-green.svg?style=for-the-badge)](http://www.python.org)
[![MIT](https://shields.io/badge/license-MIT-green?style=for-the-badge)](https://choosealicense.com/licenses/mit/)
[![Issues](https://img.shields.io/github/issues/jonosur/pyHockeyVids?style=for-the-badge)](https://github.com/jonosur/pyHockeyVids/issues)
[![Tested](https://img.shields.io/badge/tested%20on-linux-yellow?style=for-the-badge&logo=linux&logoColor=linux)](#)

pyHockeyVids is a Python3 program using PyQT5 and requests to fetch NHL videos and play them on a connected Chromecast Device or your default Web Browser.

Team themes are available, and will update the calendar with games played.

## Requirements

Make sure you have the following libraries installed in your environment, please be aware this was developed in Linux and has not been fully tested for Windows or macOS.


```bash
PyChromecast
PyQt5
requests
wget
```

## Usage

```
python3 main.py
```

![main application](https://i.imgur.com/ZAHi68O.png)

![settings](https://i.imgur.com/YrLLUop.png)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Todo
* Use QTimer to check for new videos and announce via system tray.

## Bugs
* Once a known bug has been identified I will place it here in the README.md until the issue has been resolved.

## License
[MIT](https://choosealicense.com/licenses/mit/)
