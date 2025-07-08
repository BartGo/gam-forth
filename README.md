# GAM-FORTH and other fig-FORTH sources by Roland Pantoła

This repository features Roland Pantoła's fig-FORTH work. It includes the original "GAM-FORTH" game development environment for Atari 800XL, based on a modified APX Extended fig-FORTH but dependent mostly on its public domain "FIG" core and the Assembler by [Bill Ragsdale](https://github.com/BillRagsdale). You can find more information about Roland here:
* [Wikipedia entry (🇵🇱)](https://pl.wikipedia.org/wiki/Roland_Panto%C5%82a)
* [Moby Games entry (🇪🇳)](https://www.mobygames.com/person/483332/roland-panto%C5%82a/)

With the generous offering from Mr. Pantoła to the [Polish Society for Preserving the Technical Heritage (🇵🇱)](https://ptodt.org.pl/about/), GAM-FORTH sources are published here with his approval for the benefit of the wider Forth and Atari communities.

Main elements of GAM-FORTH are Forth enhancements, source code Editor and a complex GRAF package (able to convert and process graphics made in [RAMbrandt](https://github.com/savetz/RAMbrandt)). 

EDYTOR-FORTH (source Editor), previously published in "Tajemnice Atari":

![](dev/9a-edit-26.png)

GRAF, here in one if its modules:

![](dev/11a-graf.png)

GRAFIK-DOS (graphics storage routines):

![](dev/42a-grafdos.png)

This unique environment was used to develop 8-bit games: 
  - "A.D. 2044" (1991, 🇵🇱) - see the gameplay on [A.D. 2044 - Atari XL/XE by gregok1973 (🇵🇱)](https://www.youtube.com/watch?v=BUFI9YIeCvc). 
  - "Klątwa"/"The Curse" (1992, 🇵🇱/🇪🇳) - see the gameplay on [Klątwa for the Atari 8-bit family by Highretrogamelord (🇵🇱)](https://www.youtube.com/watch?v=ygqf9H5aB2k).
  - "Władcy Ciemności" (1993, 🇵🇱) - see the gameplay on [Władcy Ciemności - RetRozrywka GamePlay by RetRozrywka (🇵🇱)](https://www.youtube.com/watch?v=yMG_Y_y1VSs).

These three games are copyrighted by [LK Avalon](https://www.lkavalon.com/), reeditions may be available at [Retronics](https://retronics.eu/). Sources of these games are NOT available here.

"Klątwa" and "Władcy Ciemności" were also ported to Commodore C-64.

The original 5.25" floppy disks were digitized by Trub.

Review, source selection and README by BartGo (Bartosz Gołda).

## Index

| #  | Type  |  Name          | Name and Description                             | Platform    |
| -- |------ | ----------     | -----------                                      | ----------- |
| 01 |🛠️💾⚙️📝| dev/09_A_Forth.* | **FORTH+EDITOR 1.6 / EKRANY** - dev environment (compiled) | 🗻 |
| 02 |🛠️💾📝| dev/09_B_Ekrany.* | **FORTH+EDITOR 1.6 / EKRANY** - related sources ("screens") | 🗻 |
| 03 |🛠️💾⚙️📝| dev/11_A_Graf.* | **GRAF: COM / EKRANY** - resource manager / editor (compiled)     | 🗻 |
| 04 |🛠️💾📝| dev/11_B_Graf.* | **GRAF: COM / EKRANY** - resource manager / editor, sources ("screens")  | 🗻 | 
| 05 |🛠️💾⚙️ | dev/42_A_GrafDos.*   | **GRAF-DOS 2.05 / RAMB-KASETA** - resource conversion (compiled) | 🗻 |
| 06 |🛠️💾📝🖨️| dev/42_B_GrafDos.*   | **GRAF-DOS 2.05 / RAMB-KASETA** - resource conversion, sources ("screens")| 🗻 |
| 07 |🕹️💾📝| game/01_A_IronNappy.* | **IRON NAPPY EKRANY** - game concept, sources ("screens")   | 🗻 |

* 🛠️ - development tool(s)
* 💾 - floppy image in the ATR format (marked with ⚙️ whenever bootable), together with LOG files
* 🕹️ - game - sources or executable (also game concepts or prototypes)
* 📝 - sources in the TXT format (omitting special ATASCII characters and binary data)
* 🖨️ - sources in the PDF format (preserving special ATASCII characters and binary data)
* 🗻 - Atari 8-bit

Please note that "screens" are a Forth-specific way to store sources on a floppy and an alternative to filesystem. Sources stored in this way were here converted to allow more convenient browsing and analysis. Still, the "screen" concept cannot be abandoned and sources had to be also provided on the floppy images (ATR) - to preserve the correct structure.

<!--


* ✅ - available
* 🔜 - upcoming
* 📚 - game - resources (e.g. text, graphics)
* 🌈 - Commodore C-64 -->

<!-- 
## Licensing Information

This project contains various components, each with its own licensing terms.
Please consult the `LICENSE` file within each respective directory for details.
-->
