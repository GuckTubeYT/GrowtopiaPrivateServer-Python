<h1 align="center">Growtopia Private Server Python</h1>

An Growtopia private server made with python3 using enet wrapper with [pyenet](https://github.com/aresch/pyenet),

## Todo
- [X] World Handler
- [ ] Multiplayer (not tested)
- [X] World Saving
- [X] Player Saving
- [ ] Player Inventory
- [X] Player Movement
- [ ] Improvement Security
- [ ] Tile Extra Handler

## Requiredment
- python 3.13 or higher
- gcc

## Installation
```
$ python setup.py build
$ python setup.py install
```

## Run Server
```
$ python server.py
```

## Credits:
- [ENet](https://github.com/lsalzman/enet): ENet reliable UDP networking library
- [Modified Enet](https://github.com/ZTzTopia/enet/tree/20193ae48ef4bf2e7829105d7f7c9f185e580619): Modified enet ubisoft protocol
- [PyEnet](https://github.com/aresch/pyenet): An ENet Python3 Wrapper
