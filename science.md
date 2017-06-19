This details the science behind Status Effects, and will be used throughout the rest of this guide in several ways. Status Effects in Spiral Knights work on a -6 (Negative Six) to +8 (Positive Eight) scale. This scale works for both Status Resistances, and Status Strength. Understanding how this scale works will be important to understanding how Status Effects work in general. This part is long, and has been segmented to make it easier to read.

***General***: The -6 to +8 scale is a 28-point scale working in half steps (-6,-5.5,-5,-4.5, ETC) that is used in the calculation of both Status Resistance and Status Strength. For visualizing this scale in game use this image:
http://media.spiralknights.com/wiki-images/c/c0/WikiTool-StatusBars.png
\split
***Resistances***: To clarify, the blue bars going to the right are positive resistances, which will be called Resistance, and the pink bars going to the left are negative resistances, which will be called Weakness. It should be noted that this scale does not stop at +/-4, but instead goes all the way up to as far as the game allows. The maximum amount of Resistance/Weakness the game will show in the player profile is +/-8, however it can go lower and higher then the shown values. Most armors give a +4 resistance at 5 star, trinkets start at .5 resistance at 2 star and add .5 for each star level. It should be stated that all Resistances/Weakness from all armors/UVs/Trinkets/Perks will be added together to form the Total Resistance.

***Strength***: When determining the Strength of a Status there are 2 states that will be covered, "Dealing Strength" and "Received Strength". The Dealing Strength of a Status is how strong the Status that has been dealt is with no Resistance or Weakness considered, while the Received Strength is how strong a Status is after Resistances or Weakness are considered.

***Dealing Strength***: The first state is the Dealing Strength. This is how strong of a Status an attack will do. Many weapons, enemies, and pick-ups can deal some form of Status. In a menu this is shown as Minor, Moderate, and Strong. A Minor Status is a 0 Strength, a Moderate Status is a +2 Strength, and a Strong Status is a +4 Strength. It should be stated that 0 Strength Status will still deal it's status, is more-or-less the baseline strength and damage of a Status Effect. MOST enemies and traps in the Clockworks, with very few exceptions, will deal +4 Strength Status. Tier 1 vials/barriers deal +2, Tier 2 vials/barriers deal +4, and Tier 3 vials/barriers deal +6.
\split
***Received Strength***: The second, and most important, state of a Status is the Received Strength. The Received Strength is how strong the Status dealt to the recipient is. The way this is calculated is based on the following formula.

**RS = DS - TR**

RS is Recieved Strength, DS is Dealing Strength, TR is Total Resistance.

RS will ALWAYS be between -6 and +8. If the value is lower than -6 or higher than +8 it will be changed to fit inside that. For example, if DS is 0 and R is 8 then RS would be -8. Because -8 is below -6 I will round it up to -6.As said previously, most enemies in the game will do a +4 DS Status, so the eventual equation for most calculations for Enemies Against Players will be **RS = 4 - TR.**
