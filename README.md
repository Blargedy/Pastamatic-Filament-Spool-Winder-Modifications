# Pastamatic Filament Spool Winder Modifications
Modifications to [GekoPrime's](https://www.printables.com/@GekoPrime) winder to better meet my use-cases. Features braces for rigidity and alignment, as well as support for spooling from Polymaker's 5kg spools.

The friction on the leadscrew tooth was enough to have the leadscrew block jump up and pull the whole machine up with it. I created a brace that adds more stiffness than just the crossbars, and added a clamping tab for good measure. 
![20230817_211242](https://github.com/Blargedy/Pastamatic-Filament-Spool-Winder-Modifications/assets/25805271/26c2326a-4afc-4b9f-a107-ab067e391790)

The source cradle had too much skew play for my liking so I created a brace to match the target brace above.  
![20230817_211314](https://github.com/Blargedy/Pastamatic-Filament-Spool-Winder-Modifications/assets/25805271/f928e3ae-3d9c-4fe7-9714-1ff721eb10cb)

I wanted to be able to respool from Polymaker's 5kg spools, so I modified the source brace to fit the large spool. However the height of the 5kg idlers was enough that the single flat brace I used for the 3kg spools didn't suffice. I added collars that bolt together for optimal stiffness. 
![20230817_210628](https://github.com/Blargedy/Pastamatic-Filament-Spool-Winder-Modifications/assets/25805271/04e3668d-20a9-45b6-88a7-e70526963457)
![20230817_211146](https://github.com/Blargedy/Pastamatic-Filament-Spool-Winder-Modifications/assets/25805271/b59cbf07-9ac4-4586-ac8e-7e6f7c8ad499)
![20230817_211425](https://github.com/Blargedy/Pastamatic-Filament-Spool-Winder-Modifications/assets/25805271/9ad774e3-8044-477a-b44d-376d83898fad)

## Parts to Print
### From this mod
* If your printer build plate can fit the "1x_source_brace_for_5kg_spools.stl" then use that file. Otherwise, use the "*_small_bed.stl" version
* One of each file excluding the cases above

### From the original
* 1x_double_idler.stl
* 1x_leadscrew.stl
* 1x_leadscrew_pin.stl
* 1x_leadscrew_tooth.stl
* 1x_passive_target_cradle.stl
* 1x_spindle_female.stl or alternate_spindle_female_long.stl
* 1x_spindle_male_driven.stl
* 1x_spindle_male_passive.stl
* 2x_source_cradle.stl
* 5x_idler.stl
* 7x_pin_long.stl
* 8x_pin_short.stl
  
The wiper mounts were, in my experience, completely useless and only got in the way. You may try them yourself but imo they're a waste of time and filament. I also found the spindle_clip to kinda suck, but ymmv.
