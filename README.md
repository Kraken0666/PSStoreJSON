# PSStoreJSON

## Description
PSStoreJSON is a utility for collecting LittleBigPlanet™ downloadable content metadata from Playstation®Store content using the **ContentID** section from the native downloadable content locking format (a.k.a. `*.dlc`). The script uses undocumented API endpoints to collect the data.

## Installation

`gh repo clone Kraken0666/PSStoreJSON`
or
`git clone https://github.com/Kraken0666/PSStoreJSON`

##

### Usage
`python main.py <dlc file> <country> <language> <Service ID Prefix> <Title ID>`

### Example
`python main.py "downloadables.dlc" gb en EP9000 BCES00141`

### CSV Usage
`python main_csv.py`

##

### Supports
- LittleBigPlanet™ 1 (All regions/releases)
- LittleBigPlanet™ 2 (All regions/releases)
- LittleBigPlanet™ 3 (All regions/releases)

### To-Do List
- [x] Add "InGameCommerceID" support (https://github.com/Kraken0666/PSStoreJSON/pull/1)
- [x] Test with LittleBigPlanet™ PS Vita™ `*.dlc*` file
- [ ] Add LittleBigPlanet™ PS Vita™ support
- [x] Test PS4 remap `*.dlc` files
- [ ] Add PSP support (or create gist specifally for it)
- [ ] Add Karting support (or create gist specifically for it)
- [x] Add SerialStation CSV support (CSV provided courtesy of landcross on SerialStation Discord)
