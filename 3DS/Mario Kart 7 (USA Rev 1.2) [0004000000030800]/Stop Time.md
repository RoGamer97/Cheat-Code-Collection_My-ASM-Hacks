## Stop Time

This code allows you to "stop time". What it really means is that once activated, EVERYTHING EXCEPT YOUR KART WILL FREEZE! CPUs, objects, animations, items and anything else will freeze but your kart, you can move and throw items that are frozen,
deactivating the code will unfreeze everything and continue as normal. It's very fun, you can freeze time and throw frozen items in front of everyone and then resume or do other cool stuff. If enabling while objects and CPUs are out of views, they will
be invisible until code is disabled. Could not figure it disable then enable code agin for a moment to regain visibility.
This is a remake of Fosfour5933's MK7 code: https://www.youtube.com/watch?v=xz2lCAw_nzY

<details>
<summary>Reveal Code</summary>

XXXXXXXX: Button to enable code
YYYYYYYY: Button to disable code

Button values: https://gist.github.com/Nanquitas/d6c920a59c757cf7917c2bffa76de860 ("SPECIAL KEYPAD CODE")

```armv7
E068052C 00000038
E59410AC E5D08018
E3580004 B12FFF1E
E5D48164 E3580000
1A000005 E5D48156
E358000E 1594805C
13580002 13580001
012FFF1E E8BD8010
DD000000 XXXXXXXX
0015B180 E12FFF1E
0024BB80 E12FFF1E
002B68C0 00000000
002B7470 00000000
002B848C EB0F2026
002BC530 00000000
002C132C 00000000
002C3CD0 00000000
002D2458 E3A01000
002FA8AC E3560001
002FA8E4 E3560001
002FA920 E3560001
002FA984 E3560001
0032B13C E12FFF1E
0033CFFC E12FFF1E
0036DEB4 E12FFF1E
003C3768 E12FFF1E
003CE77C E12FFF1E
003CF77C E3A00001
003E3A88 E12FFF1E
0046A1C0 E12FFF1E
004DF890 E12FFF1E
0050EDAC EA000006
0050F0D8 E3A00008
D0000000 00000000
DD000000 YYYYYYYY
0015B180 E92D4010
0024BB80 012FFF1E
002B68C0 E12FFF33
002B7470 E12FFF33
002B848C E59410AC
002BC530 E12FFF33
002C132C E12FFF33
002C3CD0 E12FFF33
002D2458 E1D014D0
002FA8AC E1500006
002FA8E4 E1500006
002FA920 E1500006
002FA984 E1500006
0032B13C E92D4070
0033CFFC E92D4030
0036DEB4 E92D41F0
003C3768 E92D4070
003CE77C E5D020D4
003CF77C E5D401F2
003E3A88 E92D4010
0046A1C0 E92D4030
004DF890 E92D4070
0050EDAC ED8D0A2E
0050F0D8 E59002F4
D0000000 00000000
```
</details>