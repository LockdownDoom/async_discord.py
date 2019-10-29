# async_discord.py
An API wrapper using the pre-rewrite syntax of discord.py.

### About
After the discord.py 1.0.0 rewrite was released, the authors have been busy working on bug fixes and such things for the rewrite, and have not been able to fix bugs with pre-rewrite code. My bot, KIPP, depends on the pre-rewrite syntax and structure of discord.py, so I forked discord.py pre-rewrite in order to do bug fixes of my own.

### Installation
This package is not on PyPi, but can still be installed though pip in this fashion:
```
pip install git+https://www.github.com/LockdownDoom/async_discord.py
```

#### Note
This library still uses the alias "discord" when importing, so switching from pre-rewrite discord.py to this should be absolutely seamless.
