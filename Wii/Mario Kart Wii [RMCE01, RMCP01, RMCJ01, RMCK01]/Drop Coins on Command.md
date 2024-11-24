## Drop Coins on Command

Press activator to drop your coins. Requires "Store Player Index/Slot" and having the player slot value being stored in 0x80001504 (https://mariokartwii.com/showthread.php?tid=1511).

Works online. Can be used with "Drop/Give All Coins at Once" (https://mariokartwii.com/showthread.php?tid=2140) to drop all of them instantly.

<details>
<summary>NTSC-U</summary>

```powerpc
C252E6E4 00000009
81830000 9421FF80
BC610008 3D808034
A18CXXXX 718BYYYY
41820020 3D808000
808C1504 7C852378
3D808053 618C4F48
7D8903A6 4E800421
B8610008 38210080
60000000 00000000
```
</details>

<details>
<summary>PAL</summary>

```powerpc
C251B0C0 00000009
81830000 9421FF80
BC610008 3D808034
A18CXXXX 718BYYYY
41820020 3D808000
808C1504 7C852378
3D808053 618C9A90
7D8903A6 4E800421
B8610008 38210080
60000000 00000000
```
</details>

<details>
<summary>NTSC-J</summary>

```powerpc
C251AA40 00000009
81830000 9421FF80
BC610008 3D808034
A18CXXXX 718BYYYY
41820020 3D808000
808C1504 7C852378
3D808053 618C9410
7D8903A6 4E800421
B8610008 38210080
60000000 00000000
```
</details>

<details>
<summary>NTSC-K</summary>

```powerpc
C25090E0 00000009
81830000 9421FF80
BC610008 3D808035
A18CXXXX 718BYYYY
41820020 3D808000
808C1504 7C852378
3D808052 618C7AE8
7D8903A6 4E800421
B8610008 38210080
60000000 00000000
```
</details>