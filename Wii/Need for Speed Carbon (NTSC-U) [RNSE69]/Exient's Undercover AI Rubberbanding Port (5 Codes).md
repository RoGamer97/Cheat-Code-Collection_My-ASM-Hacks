## Exient's Undercover AI Rubberbanding Port Codes

Crazy AI Rubberbanding ported from Need for Speed Undercover Wii (Exient's Undercover) and other related codes. 
Designed to only affect cops to make them crazy but it can be modified to affect every AI

Watch this video for more detail about this code: https://youtu.be/uLocfQQyGwY

<details>
<summary>Crazy Cheating Cops (Exient's Undercover AI Rubberbanding Port)</summary>

Main rubberbanding code. Makes cops crazy. If you want every AI to rubberband (racers and your player AI), change 408202F0 to 60000000

```powerpc
C2027418 00000061
3AE00000 819B0048
2C0C0000 408202F0
38600001 3D808005
618CB448 7D8903A6
4E800421 81830000
818C000C 7D8903A6
4E800421 81830000
818C0058 7D8903A6
4E800421 81830000
818C0034 7D8903A6
4E800421 FFE00890
807B003C 38810140
81830000 818C003C
7D8903A6 4E800421
807B003C 81830000
818C0028 7D8903A6
4E800421 819B0040
8BAC00CF 2C1D0060
41810014 3BA000C0
9BAC00CF C0229CC4
D02C00A4 3AE00001
48000009 40D692B6
7D8802A6 C021000C
C00C0000 FC010040
40810010 FC01F840
40800008 FC20F890
C002A5B0 EC210032
D021000C C0E100C4
C10100C0 FC403818
C0C100C8 C0030004
FCA04018 C0630000
FC203018 EC820028
C0030008 ECA51828
EC610028 FC202018
FC402818 FC001818
D0210124 D0410120
D0010128 EC210072
EC2208BA EC20083A
3D808020 618C27D8
7D8903A6 4E800421
EC000028 FC010000
41820030 C0029C34
C0410120 EC600824
C0210124 C0010128
EC4200F2 EC2100F2
EC0000F2 D0410120
D0210124 D0010128
C0610144 C0A10124
FC001818 C0C10140
FC202818 C0810120
C0E10148 FC403018
ED21002A C1610128
FC002018 FC205818
FCC04818 ED40102A
FC003818 FC603018
FCE05018 ED01002A
FC001818 FC803818
FCA04018 EC200032
FC002018 FC402818
EC20083A FC001018
EC20083A D0810120
D0610124 D0410128
3D808020 618C27D8
7D8903A6 4E800421
EC000028 FC010000
41820030 C0029CC4
C0410120 EC600824
C0210124 C0010128
EC4200F2 EC2100F2
EC0000F2 D0410120
D0210124 D0010128
3D608055 807B003C
61643C90 81830000
818C0068 7D8903A6
4E800421 807B003C
61643C90 81830000
818C006C 7D8903A6
4E800421 38610098
38810120 38A00000
3D808033 618C7988
7D8903A6 4E800421
C8E10098 388100D8
C8C100A0 C8A100A8
C88100B0 C86100B8
C84100C0 C82100C8
C80100D0 D8E100D8
D8C100E0 D8A100E8
D88100F0 D86100F8
D8410100 D8210108
D8010110 807B003C
81830000 818C007C
7D8903A6 4E800421
807B0030 C002A900
EC2007F2 81830000
818C00B0 7D8903A6
4E800421 807B0034
60000000 00000000
C2027448 00000003
2C170000 4082000C
4E800421 48000008
38600001 00000000
```
</details>

<details>
<summary>Force Rubberbanding AI Speed</summary>

Forces Rubberbanding AI to always be at set speed rather than having speed based on player speed, it is currently set to be very fast (460kmh~). You can modify the speed by modifying the float on the first line (43000000)

```powerpc
04001894 43000000
C202741C 00000006
2C170000 41820020
807B0030 3D808000
C02C1894 81830000
818C00B0 7D8903A6
4E800421 807B0034
C021000C 00000000
```
</details>

<details>
<summary>Highway Battle Rubberbanding AI Simulator (Player AI Rubberbanding Speed Control & Auto Pilot Toggle)</summary>

This code allows your vehicle to "simulate" the Highway Battle Rubberbanding AI. Press 1, 2 and A to enable and disable auto pilot and rubberbanding for your car.
Hold D-Pad Up and D-Pad Down (for horizontal Wiimote. D-Pad Right and D-Pad Left for vertical Wiimote) to increase/decrease your rubberbanding speed. Press B to completely reset the speed back to zero

```powerpc
28626B32 F4FF0B00
C2027420 00000010
2C170000 41820070
3D608062 394BD928
7C1E5000 40820060
C03F0060 C002A900
A14B6B32 714B0400
4182000C EC210828
4800002C 714B0003
41820028 714B0002
4182000C EC21002A
48000014 EC421028
FC011040 4081000C
EC210028 D03F0060
807B0030 81830000
818C00B0 7D8903A6
4E800421 807B0034
81830000 00000000
0403AA3C 38600001
CC000000 00000000
04027420 81830000 
0403AA3C 88630298
E0000000 00000000
```
</details>

<details>
<summary>Rubberbanding AI Chases & Rams You</summary>

Rubberbanding AI will chase and ram you, very crazy and fun. Recommended to use with the "Force Rubberbanding AI Speed" code so the AIs are always moving at a constant speed, else, their speed will be based
on your speed and they won't move if you don't move

Also recommended to use with "Indestructive Cop Cars (No Damage)"

```powerpc
C2027404 00000006
2C170000 41820020
3C808062 C024D928
D02100C0 C024D92C
D02100C4 C024D930
D02100C8 388100C0
60000000 00000000
```
</details>

<details>
<summary>Rubberbanding AI Flies in the Air</summary>

Rubberbanding AI will be flying in the air rather than being on the ground. You can modify the height they fly at by modifying the float on the first line (420C0000)

```powerpc
04001898 420C0000
C2027404 00000005
2C170000 41820018
C02100C4 3D808000
C00C1898 EC21002A
D02100C4 388100C0
60000000 00000000
```
</details>
