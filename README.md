SWGoH Guild Data - GiD - Bleeps, Sweeps and Creeps
This repository stores JSON files containing data for the guild "GiD - Bleeps, Sweeps and Creeps" in the game Star Wars: Galaxy of Heroes (SWGoH).

Purpose:

These JSON files are intended for analysis by guild members to track progress, identify areas for improvement, and make informed decisions.

File Structure:

The repository uses the following file/folder structure:

memberJsons: Contains JSON files with data about guild member rosters. Each file is titled as the players' Ally Code, and contains all the data pulled from the COMLINK 
             /player endpoint.
GuildData-BSC.json: JSON file with complete data about the guild pulled from the COMLINK /guild endpoint.
GuildData-BSC_Lite.json: JSON file with a lighter amount of data for the guild only including .member and .profile.
UnitsLite.json: JSON file that contains unit (character/ships) information. This is an extremely light version of the units.json file collected from the COMLINK /data endpoint.
                The keys for the file are the CG named units, and the corresponding values are the actual in-game names in English(US) of the units.

Data Description:

The memberJson files include information such as character rosters, gear levels, and ability levels for each guild member.

Contributing:

Currently, this repository is not set up for contributions from external users.

License:

This repository is licensed under the MIT License.
