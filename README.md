# qb-multicharacter
Multi Character Feature for QB-Core Framework :people_holding_hands:

Added support for setting default number of characters per player per Rockstar license

## Dependencies
- [qb-core](https://github.com/qbcore-framework/qb-core)
- [qb-spawn](https://github.com/qbcore-framework/qb-spawn) - Spawn selector
- [qb-apartments](https://github.com/qbcore-framework/qb-apartments) - For giving the player a apartment after creating a character.
- [qb-clothing](https://github.com/qbcore-framework/qb-clothing) - For the character creation and saving outfits.
- [qb-weathersync](https://github.com/qbcore-framework/qb-weathersync) - For adjusting the weather while player is creating a character.

## Screenshots
![Character Selection](https://cdn.izmystic.dev/images/n96bfssu.jpg)
![Character Registration](https://cdn.izmystic.dev/images/gs2nucbw.jpg)

## Features
- Ability to create up to 5 characters and delete any character.
- Ability to see character information during selection.

## Installation
### Manual
- Download the script and put it in the `[qb]` directory.
- Add the following code to your server.cfg/resouces.cfg
```
ensure qbx-core
ensure qbx-multicharacter
ensure qbx-spawn
ensure qbx-apartments
ensure qbx-weathersync
```
