# MiscChanger
## Description
Allowing Players to change their CS:GO miscellaneous items (Music-Kit / Coin / Pin).

## Requirements / Dependencies:
 - [PTaH](https://github.com/komashchenko/PTaH)
 - [eItems](https://github.com/WE3CS/eItems)

## Installation:
1. [Click Here](https://github.com/Natanel-Shitrit/MiscChanger/archive/main.zip) To download the plugin.
2. Extract it into `csgo/addons/sourcemod`.
3. Make sure you installed all dependencies.
4. Add a Database configuration named `MiscChanger` so the plugin could connect to your database.

### Configuration:
To change / add / remove commands the plugin use, edit the configuration file found in `sourcemod/configs/MiscChanger`, It's pretty straightforward.

## Usage:
#### NOTE: All the commands are configurable, see `Configuration` for more information.
Each command has a built in search function, that can be used with the following template: `sm_xxxxxx <String To Search>`
### Outcomes of the search:
1. No match, a message will be printed in the chat and nothing will change.\
![No-Match](https://i.imgur.com/9L0hSuR.png)
2. 1 Match, will automatically changed to this item.\
![1-Match](https://i.imgur.com/5qBiQRY.gif)
3. More than 1 match, will open the menu with all the matches.\
![Multi-Match](https://i.imgur.com/fUWjb5e.gif)
