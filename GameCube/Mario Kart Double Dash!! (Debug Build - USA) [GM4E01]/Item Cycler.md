## Item Cycler

Allows cycling through items with D-Pad Left and D-Pad Right. You can cycle to the left (previous item) and to the right (next item). Items are infinite. Very simple to use, useful for debugging and for fun!

Only the second character (the second one you select in character selection, who starts on the back of the kart and uses items) will have items, to avoid item limits from filling up faster and to avoid a problem with the item roulette HUD (HUD was modified and included, working perfectly).

When the given item limit is reached (maximum items in play), you can't get and use it until there's room for it to be in play.

I had difficulty finding a reliable way to clear items, but after lots of experiments, I finally found a way. However, it has a side effect of keeping the shadow and particle of the item where it was cleared. I can't find a fix or a way to clear it without problems, but it's no big deal

<details>
<summary>Reveal Code</summary>

```armv7
04165234 60000000
04165244 60000000
C21665C0 00000004
80610008 2C030013
4181000C 8876FF90
90610008 2C1B0000
60000000 00000000
C223FC1C 00000015
80CDABD0 88E6FF90
3D80803C A14C0580
714B0003 41820068
8986FF8F 2C0C0000
4082005C 806602D0
2C030000 41820014
3D808025 618C5200
7D8903A6 4E800421
714B0001 41820020
38E7FFFF 2C070010
4182FFF8 2C070000
40800024 38E00013
4800001C 38E70001
2C070010 4182FFF8
2C070013 40810008
38E00000 98E6FF90
90E60254 38E00010
90E6024C 714A0003
39800001 40820008
39800000 9986FF8F
808DA428 00000000
C222ED20 00000002
2C1E0000 41820008
5460063F 00000000
04255204 38A0000A
04255210 90A30118
```
</details>