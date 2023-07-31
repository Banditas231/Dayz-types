# Dayz-types EN
Dayz types.xml

To use them you need create new folder in DayZServer\mpmissions\dayzOffline.chernarusplus(NAME OF YOUR FOLDER) 
So mine looks like this:⤵️

DayZServer\mpmissions\dayzOffline.chernarusplus\CustomTypes

Next step is add lines in cfgeconomycore.xml
So add this:⤵️

<ce folder="CustomTypes/ChernoTypes">
        <file name="types_clothes.xml" type="types" />
		<file name="types_containers.xml" type="types" />
		<file name="types_explosives.xml" type="types" />
		<file name="types_food.xml" type="types" />
		<file name="types_other.xml" type="types" />
		<file name="types_tools.xml" type="types" />
		<file name="types_vehicles.xml" type="types" />
		<file name="types_vehiclesparts.xml" type="types" />
		<file name="types_weapons.xml" type="types" />
</ce>

Last step: in DayZServer\mpmissions\dayzOffline.chernarusplus\db folder open types.xml and remove all just keep like mine:⤵️

<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<types>

</types>

Game need have that file anyway , or it not gonna work.
Before making any changes always back up your server files !!!
