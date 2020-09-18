# SpaceBori’s resource patches

 A set of ModuleManager patches to manipulate resources.

 No new parts, no dlls.

 Requires ModuleManager and Community Resource Pack. The patches are fairly simple, so it should work with any recent version.
 
 Intended to be used with Real Fuels or Coherent Resource System

## SB’s ISRU Plus
 Adds water electrolysis, to produce LqdHydrogen and LqdOxygen from water, and Sabatier, to produce water and LqdMethane from  LqdHydrogen and Carbon dioxide, to the stock ISRU. (Disabled when Coherent resource System is installed.)
 Adds water pumps to the stock drills. (Disabled when Coherent resource System is installed.)
 Adds a LqdOxygen to Oxygen decompressor to all crewed command pods. (Only enabled when Tac-LS is installed)
 And adds Nitrogen, Methane and LqdMethane as planetary resources.

 No game breaking dependencies, though quite useless without mods that use those resources. 

## SB’s No LFO
 Removes or replaces Liquid Fuel, Oxidizer and Monopropellant with Kerosine, LqdOxygen and Hydrazine where RealFuels didn't do that already.

 Requires Real Fuels, just because the game will be unplayable without any fuel.
 
## SB’s crude oil
 Adds the planetary resource Oil to Kerbin. 
 Adds the option to pump oil to the stock drills. (Crude Oil 90% + Natural Gas (primarly Methane) 10% (DumpExcess = true))
 Adds the Oil refinery to the stock ISRU to create LiquidFuel or Kerosine (wth Real Fuels installed). (Input: Oil Output: 15% Kerosine/LiquidFuel + 1% LqdMethane (DumpExcess = true))

 No game breaking dependencies, with Real Fuels installed it outputs Kerosine instead of Liquid Fuel.

## SB's No Rocketparts
 Replace Rocketparts with Materialkits In Sciencelab when MKS is installed
 
## SB's CLS patches
 Adds CLS patches to the Large Probe, Large SAS and the Large TACLS Recyclers

# Notes
 18.09.2020: Testing on 1.10.1 now (with RealFuels again)
 24.04.2018: I switched to 1.4.2, so I will not test on 1.3.1 anymore, which means I will not make any changes to the parts that depend on RealFuels. 
 
# TO DO

 - Figure out the correct order and mod dependencies and replace ":FINAL”
 - Figure out how to add fuels to FSFuelSwitch. (Only neccessary for use with RealFuels)
 - Create patches to replace LFO and Monopropellent and add Kerosine, LqdHydrogen and Hydrazine when RealFuels isn't installed. 
 - Get the numbers right.
 - Change the composition of Layhte to be more like Titan.
 - Find which mods changes rocketparts to materialkits and submit the sciencelab patch to the mod author.
 - Test, test, test

