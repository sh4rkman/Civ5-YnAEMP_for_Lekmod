# YnAEMP for Lekmod

A Yet (not) Another Earth Map Pack version compatible with [Lekmod](https://docs.google.com/document/d/18tsjg2C1wKA7I41GktDRr6R83eUrhn4FHi9EUEtpKvI/edit).

This Civilization V mod is an altered version of Gedemon's last version, with a few features :
- True Start Location for the [34 new civs](https://docs.google.com/document/d/1Yy9z-pe9D4S_poTCRzLxmWCalY3QAo2MhGbuV17HmYM/edit) from Lekmod 29.1 (Giant Earth only for the moment)
- Minor map fixes for the new civs
- A few rules changes to avoid overcrowded area and city spamming :
	- The mod look for civilizations with TSL too close to each others and delete them
	- Cities can't be settled less than 6 tiles away from another city


See complete changelog below.  



# Installation

Download the lastest release and unpack it in your Civilization V mod folder :  

	- C:\Users\XXXX\Documents\My Games\Sid Meier's Civilization 5\MODS

![MODS Folder](https://i.imgur.com/OtEsU3M.png)

- launch civ5, go to the mod browser and activate the mod.
- from the mod section, go to single player and then to custom game
- do not use the classic set up game option, to get the new advanced setup menu, you must go in custom game, then select "Yet (not) Another Earth Maps" and click on Load Mod


# Map Supported for now

This mod contain custom files (CivilizationsStartPos.xml and MinorCivStartPos.xml) that only add True Start Locations for the Yet (not) Another Giant Earth Map. More maps will be coming if i find the motivation.

| Map | Size | Supported |
| :- | :-: | :-: |
| Giant Earth Map | 180x94 | :heavy_check_mark: |
| Giant Europe map? |  | :heavy_multiplication_x: |
| Giant South-East Asia map ? |  | :heavy_multiplication_x: |



# Complete changelog

**v1.0** _(Sept. 26 2021)_ :
- Added Lekmod compatibility for YnAEMP :
	- Added TSL for the 34 new civs from Lekmod
	- Corrected
- Giant Earth Map : 
	- Added Fountain of Youth in Florida 
	- Added more hills in Himalayas
	- Added more attols to Hawaii/Tonga/Cuba so they have a less shitty start
	- Added 1 tile to Tonga to let their starter warrior spawn
	- Added two tiles to Cuba
	- Added a few jungle/marshes tiles in Vietnam
	- Ottomans and Byzantium now start west side of Bosphorus when "Bosphorus is a sea" is checked
- TSL and civ distribution :
	- Added a rule so that no civ can spawn close to each others : a civ with a TSL <7 tiles to another is deleted
	- Added a rule so that no civ can place a city less than 6 tiles away from another city
- MISC 
    - Now sorting custom civilizations by alphabetical order at game setup


