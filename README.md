# Bart_Tweaks<br/>
1. No Reputation Loss from Slayer Form (Cheat)<br/>
2. Debug Ring (Cheat)<br/>
3. No Random Treasures<br/>
4. Droppable/Movable NPC Items<br/>
5. Revised Shapeshifting for SCS<br/>
6. Set Summonable Flag<br/>
7. Alternative Sorcerer Spell Progression<br/>
8. Alternative Weapon Mastery<br/>
9. Alternative Wisdom Bonus Spells<br/>
10. Alternative Constitution Bonuses<br/>

## No Reputation Loss from Slayer Form<br/>
Makes it so there is no reputation penalty from transforming into the Slayer. Should also affect Ascension's Ravager transformation.<br/>

## Debug Ring<br/>
While anyone is wearing it, grants the enitre party: immunity to damage, magic, and most harmful effects, a huge THAC0 and damage boost, instant and aura-cleansing spellcasting, massive regeneration, a large movement speed bonus, the ability to restore spells, charm (with no hostile reaction) and kill creatures (while getting credit/XP), and some other utility abilities. Add to inventory via console: "CLUAConsole:CreateItem("RINGKILL").<br/>

## No Random Treasures<br/>
Removes all random treasures from every creature in the game's inventories. Almost all of it is worthless and simply annoying/busybody work.<br/>

## Droppable/Movable NPC Items<br/>
Affects Nalia's Ring, Edwin's Amulet, Minsc's Boo, Alora's Rabbit Foot, Xan's Moonblade, Eldoth's Poisoned Arrows.<br/>

## Revised Shapeshifting for SCS<br/>
Hijacks SCS' improved shapeshifting tokens, rewrites their descriptions to the SRR/IRR format, and slightly revises some of their stats. Requires SCS's improved shapeshifting component to actually be installed to work.<br/>

## Set Summonable Flag<br/>
Sets the "is a summonable" flag for all vanilla, SR, and atweaks creatures. Some mods, including atweaks itself, set these incorrectly and therefore must be patched late into the install to function correctly. Should correctly detect and work with "no summonables limits" mods. Does not actually need either SR or atweaks to be installed if you're using it for some other purpose - it will simply patch their creatures if it detects them being there.<br/>

## Alternative Sorcerer Spell Progression<br/>
The overall effect is that sorcerers get more powerful by initially having both less spell selections and number of casts, but having them scale better and much more sensibily over time. Furthermore, now sorcerers also have the same spellcasting level progression as base class mages (previously, they progressed a bit slower). Compare at level 7 from vanilla to new for a good idea on how it shifts spell progression to be more sensible. Heavily based on Anthology Tweaks' P&P spell progression table for mages, refitted for sorcerers.<br/>

### Vanilla Spell Selection:<br/>
1st Level: 2, 0, 0, 0, 0, 0, 0, 0, 0 (2x 1st)<br/>
2nd Level: 2, 0, 0, 0, 0, 0, 0, 0, 0 (0th)<br/>
3rd Level: 3, 0, 0, 0, 0, 0, 0, 0, 0 (1st)<br/>
4th Level: 3, 1, 0, 0, 0, 0, 0, 0, 0 (2nd)<br/>
5th Level: 4, 2, 0, 0, 0, 0, 0, 0, 0 (1st, 2nd)<br/>
6th Level: 4, 2, 1, 0, 0, 0, 0, 0, 0 (3rd)<br/>
7th Level: 5, 3, 2, 0, 0, 0, 0, 0, 0 (1st, 2nd, 3rd)<br/>
8th Level: 5, 3, 2, 1, 0, 0, 0, 0, 0 (4th)<br/>
9th Level: 5, 4, 3, 2, 0, 0, 0, 0, 0 (2nd, 3rd, 4th)<br/>
10th Level: 5, 4, 3, 2, 1, 0, 0, 0, 0 (5th)<br/>
11th Level: 5, 5, 4, 3, 2, 0, 0, 0, 0 (2nd, 3rd, 4th, 5th)<br/>
12th Level: 5, 5, 4, 3, 2, 1, 0, 0, 0 (6th)<br/>
13th Level: 5, 5, 4, 4, 3, 2, 0, 0, 0 (4th, 5th, 6th)<br/>
14th Level: 5, 5, 4, 4, 3, 2, 1, 0, 0 (7th)<br/>
15th Level: 5, 5, 4, 4, 4, 3, 2, 0, 0 (5th, 6th, 7th)<br/>
16th Level: 5, 5, 4, 4, 4, 3, 2, 1, 0 (8th)<br/>
17th Level: 5, 5, 4, 4, 4, 3, 3, 2, 0 (7th, 8th)<br/>
18th Level: 5, 5, 4, 4, 4, 3, 3, 2, 1 (9th)<br/>
19th Level: 5, 5, 4, 4, 4, 3, 3, 3, 2 (8th, 9th)<br/>
20th Level: 5, 5, 4, 4, 4, 3, 3, 3, 3 (9th)<br/>
21st Level: 5, 5, 4, 4, 4, 4, 3, 3, 3 (7th)<br/>
22nd Level: 5, 5, 5, 4, 4, 4, 4, 3, 3 (3rd, 8th)<br/>
23rd Level: 5, 5, 5, 5, 4, 4, 4, 4, 3 (4th, 8th)<br/>
24th Level: 5, 5, 5, 5, 4, 4, 4, 4, 3 (0th)<br/>
25th Level: 5, 5, 5, 5, 4, 4, 4, 4, 4 (9th)<br/>
26th Level: 5, 5, 5, 5, 4, 4, 4, 4, 4 (0th)<br/>
27th Level: 5, 5, 5, 5, 4, 4, 4, 4, 4 (0th)<br/>
28th Level: 5, 5, 5, 5, 5, 4, 4, 4, 4 (5th)<br/>
29th Level: 5, 5, 5, 5, 5, 4, 4, 4, 4 (0th)<br/>
30th Level: 5, 5, 5, 5, 5, 5, 4, 4, 4 (6th)<br/>
31st Level: 5, 5, 5, 5, 5, 5, 5, 4, 4 (7th)<br/>
32nd Level: 5, 5, 5, 5, 5, 5, 5, 5, 4 (8th)<br/>
33rd Level: 5, 5, 5, 5, 5, 5, 5, 5, 4 (0th)<br/>
34th Level: 5, 5, 5, 5, 5, 5, 5, 5, 4 (0th)<br/>
35th Level: 5, 5, 5, 5, 5, 5, 5, 5, 4 (0th)<br/>
36th Level: 5, 5, 5, 5, 5, 5, 5, 5, 5 (9th)<br/>
37th Level: 5, 5, 5, 5, 5, 5, 5, 5, 5 (0th)<br/>
38th Level: 5, 5, 5, 5, 5, 5, 5, 5, 5 (0th)<br/>
39th Level: 5, 5, 5, 5, 5, 5, 5, 5, 5 (0th)<br/>
40th Level: 5, 5, 5, 5, 5, 5, 5, 5, 5 (0th)<br/>

### New Spell Selection:<br/>
1st Level: 1, 0, 0, 0, 0, 0, 0, 0, 0 (1st)<br/>
2nd Level: 2, 0, 0, 0, 0, 0, 0, 0, 0 (1st)<br/>
3rd Level: 2, 1, 0, 0, 0, 0, 0, 0, 0 (2nd)<br/>
4th Level: 3, 2, 0, 0, 0, 0, 0, 0, 0 (1st, 2nd)<br/>
5th Level: 4, 2, 1, 0, 0, 0, 0, 0, 0 (1st, 3rd)<br/>
6th Level: 4, 2, 2, 0, 0, 0, 0, 0, 0 (3rd)<br/>
7th Level: 4, 3, 2, 1, 0, 0, 0, 0, 0 (2nd, 4th)<br/>
8th Level: 4, 3, 3, 2, 0, 0, 0, 0, 0 (3rd, 4th)<br/>
9th Level: 4, 3, 3, 2, 1, 0, 0, 0, 0 (5th)<br/>
10th Level: 4, 4, 3, 2, 2, 0, 0, 0, 0 (2nd, 5th)<br/>
11th Level: 4, 4, 4, 3, 3, 0, 0, 0, 0 (3rd, 4th, 5th)<br/>
12th Level: 4, 4, 4, 4, 4, 1, 0, 0, 0 (4th, 5th, 6th)<br/>
13th Level: 5, 5, 5, 4, 4, 2, 0, 0, 0 (1st, 2nd, 3rd, 6th)<br/>
14th Level: 5, 5, 5, 4, 4, 2, 1, 0, 0 (7th)<br/>
15th Level: 5, 5, 5, 5, 5, 2, 1, 0, 0 (4th, 5th)<br/>
16th Level: 5, 5, 5, 5, 5, 3, 2, 1, 0 (6th, 7th, 8th)<br/>
17th Level: 5, 5, 5, 5, 5, 3, 3, 2, 0 (7th, 8th)<br/>
18th Level: 5, 5, 5, 5, 5, 3, 3, 2, 1 (9th)<br/>
19th Level: 5, 5, 5, 5, 5, 3, 3, 3, 1 (8th)<br/>
20th Level: 5, 5, 5, 5, 5, 4, 3, 3, 2 (6th, 9th)<br/>
21st Level: 5, 5, 5, 5, 5, 4, 4, 4, 2 (7th, 8th)<br/>
22nd Level: 5, 5, 5, 5, 5, 5, 4, 4, 3 (6th, 9th)<br/>
23rd Level: 5, 5, 5, 5, 5, 5, 5, 5, 3 (7th, 8th)<br/>
24th Level: 5, 5, 5, 5, 5, 5, 5, 5, 4 (9th)<br/>
25th Level: 5, 5, 5, 5, 5, 5, 5, 5, 4 (0th)<br/>
26th Level: 6, 6, 6, 6, 6, 5, 5, 5, 5 (1st, 2nd, 3rd, 4th, 5th, 9th)<br/>
27th Level: 6, 6, 6, 6, 6, 6, 6, 5, 5 (6th, 7th)<br/>
28th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (8th, 9th)<br/>
29th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
30th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
31st Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
32nd Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
33rd Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
34th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
35th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
36th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
37th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
38th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
39th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
40th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
41st Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
42nd Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
43rd Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
44th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
45th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
46th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
47th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
48th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
49th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
50th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>

### Vanilla Spell Table:<br/>
1st Level: 3, 0, 0, 0, 0, 0, 0, 0, 0 (3x 1st)<br/>
2nd Level: 4, 0, 0, 0, 0, 0, 0, 0, 0 (1st)<br/>
3rd Level: 5, 0, 0, 0, 0, 0, 0, 0, 0 (1st)<br/>
4th Level: 6, 3, 0, 0, 0, 0, 0, 0, 0 (1st, 3x 2nd)<br/>
5th Level: 6, 4, 0, 0, 0, 0, 0, 0, 0 (2nd)<br/>
6th Level: 6, 5, 3, 0, 0, 0, 0, 0, 0 (2nd, 3x 3rd)<br/>
7th Level: 6, 6, 4, 0, 0, 0, 0, 0, 0 (2nd, 3rd)<br/>
8th Level: 6, 6, 5, 3, 0, 0, 0, 0, 0 (3rd, 3x 4th)<br/>
9th Level: 6, 6, 6, 4, 0, 0, 0, 0, 0 (3rd, 4th)<br/>
10th Level: 6, 6, 6, 5, 3, 0, 0, 0, 0 (4th, 3x 5th)<br/>
11th Level: 6, 6, 6, 6, 4, 0, 0, 0, 0 (4th, 5th)<br/>
12th Level: 6, 6, 6, 6, 5, 3, 0, 0, 0 (5th, 3x 6th)<br/>
13th Level: 6, 6, 6, 6, 6, 4, 0, 0, 0 (5th, 6th)<br/>
14th Level: 6, 6, 6, 6, 6, 5, 3, 0, 0 (6th, 3x 7th)<br/>
15th Level: 6, 6, 6, 6, 6, 6, 4, 0, 0 (6th, 7th)<br/>
16th Level: 6, 6, 6, 6, 6, 6, 5, 3, 0 (7th, 3x 8th)<br/>
17th Level: 6, 6, 6, 6, 6, 6, 6, 4, 0 (7th, 8th)<br/>
18th Level: 6, 6, 6, 6, 6, 6, 6, 5, 3 (8th, 3x 9th)<br/>
19th Level: 6, 6, 6, 6, 6, 6, 6, 6, 4 (8th, 9th)<br/>
20th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (2x 9th)<br/>
21th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
22th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
23th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
24th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
25th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
26th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
27th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
28th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
29th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
30th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
31th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
32th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
33th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
34th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
35th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
36th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
37th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
38th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
39th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>
40th Level: 6, 6, 6, 6, 6, 6, 6, 6, 6 (0th)<br/>

### New Spell Table:<br/>
1st Level: 2, 0, 0, 0, 0, 0, 0, 0, 0 (2x 1st)<br/>
2nd Level: 3, 0, 0, 0, 0, 0, 0, 0, 0 (1st)<br/>
3rd Level: 3, 2, 0, 0, 0, 0, 0, 0, 0 (2x 2nd)<br/>
4th Level: 4, 3, 0, 0, 0, 0, 0, 0, 0 (1st, 2nd)<br/>
5th Level: 5, 3, 2, 0, 0, 0, 0, 0, 0 (1st, 2x 3rd)<br/>
6th Level: 5, 3, 3, 0, 0, 0, 0, 0, 0 (3rd)<br/>
7th Level: 5, 4, 3, 2, 0, 0, 0, 0, 0 (2nd, 2x 4th)<br/>
8th Level: 5, 4, 4, 3, 0, 0, 0, 0, 0 (3rd, 4th)<br/>
9th Level: 5, 4, 4, 3, 2, 0, 0, 0, 0 (2x 5th)<br/>
10th Level: 5, 5, 4, 3, 3, 0, 0, 0, 0 (2nd, 5th)<br/>
11th Level: 5, 5, 5, 4, 4, 0, 0, 0, 0 (3rd, 4th, 5th)<br/>
12th Level: 5, 5, 5, 5, 5, 2, 0, 0, 0 (4th, 5th, 2x 6th)<br/>
13th Level: 6, 6, 6, 5, 5, 3, 0, 0, 0 (1st, 2nd, 3rd, 6th)<br/>
14th Level: 6, 6, 6, 5, 5, 3, 2, 0, 0 (2x 7th)<br/>
15th Level: 6, 6, 6, 6, 6, 3, 2, 0, 0 (4th, 5th)<br/>
16th Level: 6, 6, 6, 6, 6, 4, 3, 2, 0 (6th, 7th, 2x 8th)<br/>
17th Level: 6, 6, 6, 6, 6, 4, 4, 3, 0 (7th, 8th)<br/>
18th Level: 6, 6, 6, 6, 6, 4, 4, 3, 2 (2x 9th)<br/>
19th Level: 6, 6, 6, 6, 6, 4, 4, 4, 2 (8th)<br/>
20th Level: 6, 6, 6, 6, 6, 5, 4, 4, 3 (6th, 9th)<br/>
21th Level: 6, 6, 6, 6, 6, 5, 5, 5, 3 (7th, 8th)<br/>
22th Level: 6, 6, 6, 6, 6, 6, 5, 5, 4 (6th, 9th)<br/>
23th Level: 6, 6, 6, 6, 6, 6, 6, 6, 4 (7th, 8th)<br/>
24th Level: 6, 6, 6, 6, 6, 6, 6, 6, 5 (9th)<br/>
25th Level: 6, 6, 6, 6, 6, 6, 6, 6, 5 (0th)<br/>
26th Level: 7, 7, 7, 7, 7, 6, 6, 6, 6 (1st, 2nd, 3rd, 4th, 5th, 9th)<br/>
27th Level: 7, 7, 7, 7, 7, 7, 7, 6, 6 (6th, 7th)<br/>
28th Level: 7, 7, 7, 7, 7, 7, 7, 7, 7 (8th, 9th)<br/>
29th Level: 8, 8, 8, 8, 8, 7, 7, 7, 7 (1st, 2nd, 3rd, 4th, 5th)<br/>
30th Level: 8, 8, 8, 8, 8, 8, 8, 7, 7 (6th, 7th, 8th)<br/>
31th Level: 8, 8, 8, 8, 8, 8, 8, 8, 8 (8th, 9th)<br/>
32th Level: 8, 8, 8, 8, 8, 8, 8, 8, 8 (0th)<br/>
33th Level: 8, 8, 8, 8, 8, 8, 8, 8, 8 (0th)<br/>
34th Level: 9, 9, 9, 9, 9, 8, 8, 8, 8 (1st, 2nd, 3rd, 4th, 5th)<br/>
35th Level: 9, 9, 9, 9, 9, 9, 9, 8, 8 (6th, 7th)<br/>
36th Level: 9, 9, 9, 9, 9, 9, 9, 9, 9 (8th, 9th)<br/>
37th Level: 9, 9, 9, 9, 9, 9, 9, 9, 9 (0th)<br/>
38th Level: 9, 9, 9, 9, 9, 9, 9, 9, 9 (0th)<br/>
39th Level: 9, 9, 9, 9, 9, 9, 9, 9, 9 (0th)<br/>
40th Level: 9, 9, 9, 9, 9, 9, 9, 9, 9 (0th)<br/>
41th Level: 9, 9, 9, 9, 9, 9, 9, 9, 9 (0th)<br/>
42th Level: 9, 9, 9, 9, 9, 9, 9, 9, 9 (0th)<br/>
43th Level: 9, 9, 9, 9, 9, 9, 9, 9, 9 (0th)<br/>
44th Level: 9, 9, 9, 9, 9, 9, 9, 9, 9 (0th)<br/>
45th Level: 9, 9, 9, 9, 9, 9, 9, 9, 9 (0th)<br/>
46th Level: 9, 9, 9, 9, 9, 9, 9, 9, 9 (0th)<br/>
47th Level: 9, 9, 9, 9, 9, 9, 9, 9, 9 (0th)<br/>
48th Level: 9, 9, 9, 9, 9, 9, 9, 9, 9 (0th)<br/>
49th Level: 9, 9, 9, 9, 9, 9, 9, 9, 9 (0th)<br/>
50th Level: 9, 9, 9, 9, 9, 9, 9, 9, 9, (0th)<br/>

## Alternative Wisdom Spell Bonuses<br/>

### Vanilla:<br/>
The Wisdom spell bonuses for priests are incomprehensible and inconsistent, especially once you're past a wisdom score of 18. This alternative table was developed with the idea of having 18 have the same bonus spells as vanilla (18 being the "best" you can get without stat increases, and because 18's bonuses are coincidentally very logical), while smoothing out everything before and after that in a more consistent and systematic manner around the value of 18. The overall effect is that the lower wisdom scores stay mostly the same (with just a few minor shifts), while everything past 18 is slightly nerfed in the favor of consistency and sense.<br/>

13: 1, 0, 0, 0, 0, 0, 0 (1st)<br/>
14: 2, 0, 0, 0, 0, 0, 0 (1st)<br/>
15: 2, 1, 0, 0, 0, 0, 0 (2nd)<br/>
16: 2, 2, 0, 0, 0, 0, 0 (2nd)<br/>
17: 2, 2, 1, 0, 0, 0, 0 (3rd)<br/>
18: 2, 2, 1, 1, 0, 0, 0 (4th)<br/>
19: 3, 2, 1, 2, 0, 0, 0 (1st, 4th)<br/>
20: 3, 3, 1, 3, 0, 0, 0 (2nd, 4th)<br/>
21: 3, 3, 2, 3, 1, 0, 0 (3rd, 5th)<br/>
22: 3, 3, 2, 4, 2, 0, 0 (4th, 5th)<br/>
23: 3, 3, 2, 4, 4, 0, 0 (2x 5th)<br/>
24: 3, 3, 2, 4, 4, 2, 0 (2x 6th)<br/>
25: 3, 3, 2, 4, 4, 3, 1 (6th, 7th)<br/>

### New:<br/>
12: 1, 0, 0, 0, 0, 0, 0 (1st)<br/>
13: 1, 0, 0, 0, 0, 0, 0 (0th)<br/>
14: 1, 1, 0, 0, 0, 0, 0 (2nd)<br/>
15: 2, 1, 0, 0, 0, 0, 0 (1st)<br/>
16: 2, 1, 1, 0, 0, 0, 0 (3rd)<br/>
17: 2, 2, 1, 0, 0, 0, 0 (2nd)<br/>
18: 2, 2, 1, 1, 0, 0, 0 (4th)<br/>
19: 3, 2, 2, 1, 0, 0, 0 (1st, 3rd)<br/>
20: 3, 2, 2, 1, 1, 0, 0 (5th)<br/>
21: 3, 3, 2, 2, 1, 0, 0 (2nd, 4th)<br/>
22: 3, 3, 2, 2, 1, 1, 0 (6th)<br/>
23: 3, 3, 3, 2, 2, 1, 0 (3rd, 5th)<br/>
24: 3, 3, 3, 2, 2, 1, 1 (7th)<br/>
25: 3, 3, 3, 3, 2, 2, 1 (4th, 6th)<br/>

## Alternative Constitution Bonuses</br>
3rd Edition-style Constitution, with the addition of some very slow regeneration that makes resting actually have some value if you have high Constitution characters but no clerical healing spells. A character with a Constitution of 10 would receive exactly one more hitpoint from resting for 8 hours, while a character with a Constitution of 18 would receive just two more hitpoints, with a much bigger scaling up once you go beyond that into exceptional constitution territory. It doesn't sound like much, but it wasn't designed to be powerful, just to help a little in the early stages of BG1 when you don't have enough healing spells readily available and you find resting 3 times in a row to be distasteful.

01: -3 HP on level up, no regeneration, -5 fatigue bonus<br/>
02: -2 HP on level up, no regeneration, -4 fatigue bonus<br/>
03: -2 HP on level up, no regeneration, -4 fatigue bonus<br/>
04: -2 HP on level up, no regeneration, -3 fatigue bonus<br/>
05: -2 HP on level up, no regeneration, -3 fatigue bonus<br/>
06: -1 HP on level up, no regeneration, -2 fatigue bonus<br/>
07: -1 HP on level up, no regeneration, -2 fatigue bonus<br/>
08: -1 HP on level up, no regeneration, -1 fatigue bonus<br/>
09: -1 HP on level up, no regeneration, -1 fatigue bonus<br/>
10: 0 HP on level up, 1 hp/2400 second regeneration, 0 fatigue bonus<br/>
11: 0 HP on level up, 1 hp/2400 second regeneration, 0 fatigue bonus<br/>
12: 1 HP on level up, 1 hp/2100 second regeneration, 1 fatigue bonus<br/>
13: 1 HP on level up, 1 hp/2100 second regeneration, 1 fatigue bonus<br/>
14: 2 HP on level up, 1 hp/1800 second regeneration, 2 fatigue bonus<br/>
15: 2 HP on level up, 1 hp/1800 second regeneration, 2 fatigue bonus<br/>
16: 3 HP on level up, 1 hp/1500 second regeneration, 3 fatigue bonus<br/>
17: 3 HP on level up, 1 hp/1500 second regeneration, 3 fatigue bonus<br/>
18: 4 HP on level up, 1 hp/1200 second regeneration, 4 fatigue bonus<br/>
19: 4 HP on level up, 1 hp/900 second regeneration, 4 fatigue bonus<br/>
20: 5 HP on level up, 1 hp/600 second regeneration, 5 fatigue bonus<br/>
21: 5 HP on level up, 1 hp/300 second regeneration, 5 fatigue bonus<br/>
22: 6 HP on level up, 1 hp/240 second regeneration, 6 fatigue bonus<br/>
23: 6 HP on level up, 1 hp/180 second regeneration, 6 fatigue bonus<br/>
24: 7 HP on level up, 1 hp/120 second regeneration, 7 fatigue bonus<br/>
25: 7 HP on level up, 1 hp/60 second regeneration, 7 fatigue bonus<br/>
