# Garnet_exile_traders
These files are traders configuration for arma 3 exile server that I run.<br />
Feel free to copy them on your arma 3 exile server and edit them as you wish.<br />

## Mods used:
RHSAFRF https://steamcommunity.com/sharedfiles/filedetails/?id=843425103<br />
RHSGREF https://steamcommunity.com/sharedfiles/filedetails/?id=843593391<br />
RHSSAF https://steamcommunity.com/sharedfiles/filedetails/?id=843632231<br />
RHSUSAF https://steamcommunity.com/sharedfiles/filedetails/?id=843577117<br />

## How to use?
In ItemList.hpp are class names of items you want to players be able sell/purchase with prices<br />
TraderCategories.hpp are categories for traders<br />
CfgTrader.hpp are categories assigned to specific trader<br />

to run it on your server you need in your mission file config.cpp<br />
in class CfgTraderCategories comment all your code and add #include "pathToFile\TraderCategories.hpp"<br />
in class CfgTraders comment all your code and add #include "pathToFile\CfgTraders.hpp"<br />
in class CfgExileArsenal comment all your code and add #include "pathToFile\ItemList.hpp"<br />
