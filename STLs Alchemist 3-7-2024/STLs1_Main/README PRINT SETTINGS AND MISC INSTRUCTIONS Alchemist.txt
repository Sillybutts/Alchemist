ALCHEMIST BLASTER FILESET README.
By Sillybutts. 3/7/2024
---------------------------------------------------------------------------------------------
Hardware list and bar specs: https://docs.google.com/spreadsheets/d/1YDkzYdij77of0HTidGjQzjRrs53viwXQVmcyhZj8VQ8/edit?usp=sharing


Assembly video: https://youtu.be/UOdZIeP3myw?si=pLHplAR6F4LWGuP2
---------------------------------------------------------------------------------------------

Print settings:

All STLs are exported in their correct print orientations.

Black
- 100% infill, 5 walls: MagwellChin, PlungerRod, NStrikeLug.
- 10% infill, 5 walls: FixedStock_Buttplate, TriggerGuard.
- Everything else 20% infill, 5 walls
- Supports needed for MagwellChin and NStrikeLug. RailA/B/C has built in supports, no slicer supports required.
- MagwellChin MUST BE PRINTED WITH A BRIM AND SUPPORTS, and with the long bottom area facing the print bed. 

Green
- 100% infill, 5 walls: EndCap
- 10% infill, 5 walls: FixedStock_Stock.
- Everything else 20% infill, 5 walls
- Supports needed for BarrelShroudFront, BarrelShroudBack.
- EndCap is intended to print with the back facing the print bed, but it can be printed with the opposite face on the print bed if you enable supports.

Orange
- 20% infill, 5 walls: FrontGripKeeper, MagRelease, MuzzleNut, Trigger, PrimingBlock.
- Everything else 100% (full) infill, 5 walls
- No supports.
- Muzzle needs to be printed with the front facing the print bed.
- BarTensioner needs to be printed with the nut-cavity facing up.
- Brims are very helpful for printing all these orange parts.
- PrimingBlock has some overhangs, but nothing too awful. DO NOT USE SUPPORTS ON IT.

---------------------------------------------------------------------------------------------

Misc notes:

- WATCH THE ASSEMBLY VIDEO, IT IS VERY IMPORTANT.

- Use the "PT gauge" misc print to trim a TC plunger tube to Skewer length, or check which one you have.
- Use the "BarDrillingJig A/B" to make your own bars. Glue together the two prints at the "tooth" edge. 
- Life pro tip: put the bearings into the PrimingBlock slots with needle nose pliers, its easier to line up with the pockets.
- The PrimingBlock bearing slots have adjustability, make sure its as close to the barrel/bars as possible without having undue friction. 
- Lubing the outsides of the ball bearings can make things a little bit smoother if desired.
- The little screw to keep the barrel in place is optional, the blaster works fine using just the printed muzzle nut+o-ring.
- The barrel screw goes into a square nut. The square nut goes into the front of the FrontShroud part, and is held in by a 4-40 screw next to the nut.
- If the plunger isn't catching, make sure the bars are tensioned all the way, and that you have the rubber plunger padding installed.
- The plunger uses 2x M3x16 screws, 1x M3x30 screw.
- Slide the ram into RamBaseFront before putting on the 3x 012 o-rings (two on the tip, one around the bottom, which is then squeezed by the RamBaseBack to make an air seal).
- Make sure the ram is straight when tightening the 4 locking 4-40 screws.

---------------------------------------------------------------------------------------------

March 3/7/2024 update notes:

List of changed parts in this update:
- DetentBlock
- FrontGrip
- Grip_Left (and Lynx variant)
- Grip_Right (and Lynx variant)
- GripBody (all variants)
- MagwellBack
- PicKeeper (the part that inserts into the FrontGrip and the Skeggox stock)
- Plunger Head (A and B)
- Plunger Rod (all variants)
- PTback (and Skeggox stock version)
- All picatinny rails (A,B,C,Csmooth,Cskeggox)
- Sear
- Trigger
- Skeggox_Top
- Skeggox_Bottom

I recommend that people who already own Alchemists switch to using the new PlungerRod, Sear, and Trigger. This will improve catch reliability. 
These 3 parts can be installed in existing Alchemists, you just need to take off the stock and install the sear from behind the PTback. 
The new plunger rod and sear are marked with 'V2' on the side.


I also recommend that people remove the previously optional extra spring that went beneath the trigger. 
The spring works for some people (to make the trigger pull lighter), but the reliability issues for other people isn't worth the headache. So it is fully removed.

The FrontGrip, Skeggox_Bottom, and all the PicKeepers were tightened in this update. If your print tolerances do not allow for this change, the old looser files are in the Extras STL folder.

---------------------------------------------------------------------------------------------

Full changelog:

- Changelog: 10-14-2023: Blaster release.
- Changelog: 3-7-2024: A bunch of updates. 
- - Updated the sear and the plunger rod to be more wear-resistant and smoother to prime. Both these parts can be installed in existing Alchemists, you just need to take off the stock and install the sear from behind the PTback. The new plunger rod and sear are marked with 'V2' on the side.
- - Updated the PTback and Skeggox PTback to have space to install the new style of sear from the front without stock disassembly in the future. 
- - Updated the Skeggox PTback to have more space for the head of the large top bolt, and more space for the screwdriver. 
- - Removed the optional secondary trigger spring. The slight benefit in trigger feel is not worth the catch issues it causes for some people. 
- - Thinned the walls on the built in supports for the picatinny rails. Used to be 1mm wide, now 0.5mm wide.
- - Tightened the picatinny keepers for the pump grip and the Skeggox stock (upon recommendation from OOD).
- - Lengthened the Skeggox picatinny rail a HAIR to fix a tolerance (upon recommendation from OOD).
- - Added two pins to the back of the Skeggox picatinny to reinforce it. The pins go into new holes in the Skeggox PTback. 
- - Extended the sear spring a little bit more via a new optional grip print.
- - Chamfered the front bottom edges of the grip panels to better clear the mag release. (same for the Lynx-grip version's grip panels). 
- - Tightened the ball detent hole by a hair. 
- - Tweaked the MagwellBack to have more mag release clearance.
- - Added a TOP marking to the top of the trigger.
- - Extended the part of the trigger that touches the sear by a little bit to remove some slop.
