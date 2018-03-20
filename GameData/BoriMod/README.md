SpaceBori’s resource patches

 A set of ModuleManager patches to manipulate resources.

 No new parts, no dlls.

 Requires ModuleManager. The patches are fairly simple, so it should work with any recent version.

SB’s crude oil
 Adds the planetary resource Oil to Kerbin. 
 Adds the option to pump oil to the stock drills.
 Adds the Oil refinery to the stock ISRU to create Kerosine.

 No game breaking dependencies, but without Real Fuels Kerosine is pretty useless.

SB’s ISRU Plus
 Adds water electrolysis, to produce LqdHydrogen and LqdOxygen from water, and Sabatier, to produce water and LqdMethane from  LqdHydrogen and Carbon dioxide, to the stock ISRU.
 Adds methane and water pumps to the stock drills.
 Adds a LqdOxygen to Oxygen decompressor to all crewed command pods.
 And adds Nitrogen, Methane and LqdMethane as planetary resources.

 No game breaking dependencies, though quite useless without mods that use those resources. 
 The decompressor is only enabled when Tac-LS is installed.

SB’s No LFO
 Removes or replaces Liquid Fuel, Oxidizer and Monopropellant with Kerosine, LqdOxygen and Hydrazine where RealFuels didn't do  that already.

 Requires Real Fuels, just because the game will be unplayable without any 




Processes (numbers are mostly guesswork):

Drilling/Pumping:
Ore (Stock)
Crude Oil 90% + Natural Gas (primarly Methane) 10% (DumpExcess = true)
Water
? more to be added
Refining (ISRU):
Kerosine: Input: Oil Output: 15% Kerosine + 1% LqdMethane (DumpExcess = true)

Hydrogen from Methane: Input: Methane Output: 75% Hydrogen + CO2 (DumpExcess = true)

Hydrogen from Water

(Lqd)Methane: Input: Oil + CO2? Output: (Lqd)Methane +?

Hydrogen: Input: Oil Output: Hydrogen + Methane

? more to be added

Remove Liquid Fuel etc from ISRU

Replace Rocketparts with Materialkits

TO DO

Test

Figure out the correct order and mod dependencies and remove ":FINAL”
