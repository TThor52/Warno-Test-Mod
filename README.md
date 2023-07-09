# Warno-Test-Mod

Just a place to hold my changes to WARNO

Here's what's changed and in what file:

Ravitaillement.ndf:

Doubled SpecificDefaultSupplyRange

Doubled zOffset (To show the player the new radius)

/-------------------------------------------------------------------/

GDConstantes.ndf:

Note: The headers are the headers commmented out i.e. //--------------Constantes Commander---------------//

//Constantes Commander

Doubled Command Zone Radius of Command Units

//Constantes Lobby

Changed time limits to 10, 20, 30, 40, 50, 60, 0(None)

//Constantes Conquest

Changed TimeBeforeEarningConquestPoints from 1.5 -> 2.0
 
Added More Scores to ConquestPossibleScores: 5000, 10000, 20000, 30000, 40000, 50000, 100000

//Constantes Economy

Adjusted base income

-CTF(Conquest) 260 -> 200
 
-Destruction 4 -> 6
 
Adjusted the time before earning income

-CTF(Conquest) 60 seconds -> 50 seconds
 
 -Destruction 4 seconds -> 5 seconds

//Constantes Destruction

Added an IncomeMultiplierToken: 'CONQ_HIGH'
 
Added an IncomeMultiplier: 1.5

//Constantes Lobby (Yes, another one near the bottom of the file)

Adjusted the Initial Starting Points (ArgentInitialSetting)

-Original = 500, 1000, 1500, 2000, 2500, 3000
 
-New = 1000, 2000, 3000, 4000, 5000, 10000

Adjust Destruction Score Limits

-Original = 3000, 4000, 5000, 6000, 8000
 
-New = 5000, 7500, 10000, 12500, 15000

Adjusted VictoryTypeDestructionLevelsTable to match above

/-------------------------------------------------------------------/

DivisionCostMatrix.ndf:

Gave all divisions 10 slots at no cost (i.e. 0 activation cost)

/-------------------------------------------------------------------/

Divisions.ndf:

15 Cards per Unit (2611 Cards in total, to make sure I changed all units)

All NATO units in Berlin Command

All PACT units in Berlin Grunpen

/-------------------------------------------------------------------/

DivisionRules.ndf:

200 Units per Card (3479 Units in total, to make sure I changed all units)

All units at all Veterencies

All NATO units in Berlin Command (Has to match Divisions file)

All PACT units in Berlin Grunpen (Has to match Divisions file)

/-------------------------------------------------------------------/

Future changes:

Deck specific

-Adjusting unit costs

Lobby specific

-Add more initial starting points and destruction points (seen in other mods)

Game-play specific

-Making certain units "Airborne" i.e. forward deploy-able

-Changing the range of all units (~1.5 to ~2 times)

-Adding more HE to tanks

-Adjusting the height of planes

UI specific

-attempt to add drop-down boxes in the lobby for mods (we'll see)

Inspiration for these changes come from other mods. Mainly used to learn how to mod WARNO.
