[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

# DiscordFkPyramids
Discord bot designed to automatically block pyramids after the third message, with other features/functionality.

## Dependencies
- Python 3.6+
- `discord.py` 1.0.0a (for stable release, see [master](https://github.com/zaxutic/Discord-FkPyramids/tree/master/) branch)
- `aiohttp` library
- `Yarl` library (<1.2)
- `websockets` library

## Installation
### Discord.py rewrite
#### Windows
```
$ python -m pip install -U git+https://github.com/Rapptz/discord.py@rewrite
```
or
```
$ pip install -U git+https://github.com/Rapptz/discord.py@rewrite
```

#### Linux/Mac OS X
```
$ python3 -m pip install -U git+https://github.com/Rapptz/discord.py@rewrite
```
or
```
$ pip3 install -U git+https://github.com/Rapptz/discord.py@rewrite
```

### Yarl
From [abccd's answer at Stack Overflow](https://stackoverflow.com/a/50177737):

*"Discord.py rewrite branch has some problems recently with its requirements.txt and aiohttp support. You need to manually install a lower version of yarl to support discord.py's required aiohttp library.*

*You need to run the following:*
```
pip install "yarl<1.2"
```
*"*

This is required for FkPyramids to run. Without it, `FkPyramids.py` exits on the first import. *(As of 4/5/18 - 8/6/18, this may have changed by the time you are reading this.)*

### Main
```
$ git clone https://github.com/zaxutic/Discord-FkPyramids.git
$ cd Discord-FkPyramids
```

## Setup 
- Clone or download this repository into a directory.
- Create a `token.txt` file and write your bot's authentication (OAuth) token to this file.

## Running
### Windows
```
$ python FkPyramids.py
```
### Linux/Mac OS X
```
$ python3 FkPyramids.py
```
## License
This project is licensed under the GNU General Public License v3.0. See [LICENSE](https://github.com/zaxutic/Discord-FkPyramids/tree/rewrite/LICENSE) for more information.
