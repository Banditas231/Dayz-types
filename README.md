# Dayz-types [EN]
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



# [LT]
Dayz types.xml

Norėdami juos naudoti, turite sukurti naują aplanką DayZServer\mpmissions\dayzOffline.chernarusplus(JŪSŲ ALANKO PAVADINIMAS) Taigi mano atrodo taip:⤵️

DayZServer\mpmissions\dayzOffline.chernarusplus\CustomTypes

Kitas žingsnis yra pridėti eilutes į cfgeconomycore.xml Taigi pridėkite tai:

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

Paskutinis veiksmas: DayZServer\mpmissions\dayzOffline.chernarusplus\db aplanke atidarykite types.xml ir pašalinkite visus, tiesiog palikite kaip mano:⤵️

<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<types>

</types>

Žaidimas vis tiek turi turėti tą failą, kitaip jis neveiks.
Prieš atlikdami bet kokius pakeitimus, visada sukurkite atsargines serverio failų kopijas!!!

