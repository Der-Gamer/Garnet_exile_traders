# Garnet_exile_traders
These files are traders configuration for arma 3 exile server that I run.
Feel free to copy them on your arma 3 exile server and edit them as you wish.

## Mods used:
RHSAFRF https://steamcommunity.com/sharedfiles/filedetails/?id=843425103
RHSGREF https://steamcommunity.com/sharedfiles/filedetails/?id=843593391
RHSSAF https://steamcommunity.com/sharedfiles/filedetails/?id=843632231
RHSUSAF https://steamcommunity.com/sharedfiles/filedetails/?id=843577117

## How to use?
In ItemList.hpp are class names of items you want to players be able sell/purchase with prices
TraderCategories.hpp are categories for traders
CfgTrader.hpp are categories assigned to specific trader

to run it on your server you need in your mission file config.cpp
in class CfgTraderCategories comment all your code and add #include "pathToFile\TraderCategories.hpp"
in class CfgTraders comment all your code and add #include "pathToFile\CfgTraders.hpp"
in class CfgExileArsenal comment all your code and add #include "pathToFile\ItemList.hpp"
