# View Distance Settings (formly known as TAW View Distance)
Simple to use GUI for ARMA 3 enabling players to quickly change and set up profiles for view distance depending on situations.


###### Installation
First drag the taw_vd folder into your mission and then in the description.ext put:
`#include "taw_vd\GUI.h"﻿

class CfgFunctions
{
    #include "taw_vd\CfgFunctions.hpp"
};
`
If CfgFunctions already exists then put:
`#include "taw_vd\CfgFunctions.hpp" in it.`

###### Notes
Example mission provided

To disable the grass Option 'None' place:
`tawvd_disablenone = true;`

To set a maximum allowed viewing distance you can put the following in your init.sqf:
`tawvd_maxRange = 12000;`
