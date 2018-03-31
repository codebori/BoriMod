# SpaceBori’s resource patches

 A set of ModuleManager patches to manipulate resources.

 No new parts, no dlls.

 Requires ModuleManager. The patches are fairly simple, so it should work with any recent version.

## SB’s crude oil
 Adds the planetary resource Oil to Kerbin. 
 Adds the option to pump oil to the stock drills. (Crude Oil 90% + Natural Gas (primarly Methane) 10% (DumpExcess = true))
 Adds the Oil refinery to the stock ISRU to create Kerosine. (Input: Oil Output: 15% Kerosine + 1% LqdMethane (DumpExcess = true))

 No game breaking dependencies, but without Real Fuels Kerosine is pretty useless.

## SB’s ISRU Plus
 Adds water electrolysis, to produce LqdHydrogen and LqdOxygen from water, and Sabatier, to produce water and LqdMethane from  LqdHydrogen and Carbon dioxide, to the stock ISRU.
 Adds methane and water pumps to the stock drills.
 Adds a LqdOxygen to Oxygen decompressor to all crewed command pods.
 And adds Nitrogen, Methane and LqdMethane as planetary resources.

 No game breaking dependencies, though quite useless without mods that use those resources. 
 The decompressor is only enabled when Tac-LS is installed.

## SB’s No LFO
 Removes or replaces Liquid Fuel, Oxidizer and Monopropellant with Kerosine, LqdOxygen and Hydrazine where RealFuels didn't do  that already.

 Requires Real Fuels, just because the game will be unplayable without any fuel.

## Replace Rocketparts with Materialkits In Sciencelab

# TO DO

 - Figure out the correct order and mod dependencies and replace ":FINAL”
 - Figure out how to add fuels to FSFuelSwitch.
 - Create patches to replace LFO and Monopropellent and add Kerosine, LqdHydrogen and Hydrazine when RealFuels isn't installed. 
 - Get the numbers right.
 - Change the composition of Layhte to be more like Titan.
 - Find which mods changes rocketparts to materialkits and submit the sciencelab patch there.
 - Test, test, test

