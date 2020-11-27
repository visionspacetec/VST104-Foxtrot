# VST104 Element Foxtrot - single MCU OBC for PC104
This repository contains the KiCad project and other documents created during the development of Element Foxtrot under [VST104 project](https://github.com/visionspacetec/VST104/). This FlatSat board is capable of hosting four PC104 format modules with LibreCube PC104 header pinout.

<p align="center">
  <br>
  <img src=/gallery/3Dexport/top.png width=60%/>
  <br><br>
  <b>Fig 1.</b> Element Foxtrot 3D visualisation.
  <br><br>
</p>

## Basic specifications
* **`modules:`** This flatsat board can accommodate up to four PC104 modules. The position and orientation of these slots are marked with silkscreen contours. Headers of the separate slots are connected in between each other concerning individual pins. Tracing of power lines is strengthened, and the ground is shared with the rest of the board.
* **`power circuitry:`** Upper part of the board carries power distribution circuitry. Power outputs of this part are connected to corresponding powerlines of PC104 slots. The usual setup is: **3.3[V], 5[V] and unregulated** - individually rated to deliver up to **5[A]** (depends on power source) to these power lines. Although different voltages in the regulated powerlines can be set by trimmers.
* **`power modes:`** A user can power this flatsat in two different modes. External power supply with standard **2[mm] JACK** or **USB-C** charger. A three-position slide switch *(on/off/on)* placed between these two connectors is used to select one or none of them. Both of the modes are rated for input voltage in range **7-14[V]** and input current up to **8[A]** for JACK mode and **6[A]** for USB-C mode.
* **`disconnection terminal:`** A set of removable jumpers is used to temporarily separate the power distribution circuitry from the rest of the flatsat. This is practical if a user needs to power the board from a different source or do not power it at all but is keen on not separating the power delivery circuitry by braking.
* **`4[mm] banana:`** After the disconnection terminal, just on the slots beginning, powerlines are placed a set of laboratory 2[mm] banana jacks. A user can use these jacks after disconnecting the corresponding terminals to point to any power or measuring device.

<p align="center">
  <br>
  <img src=/gallery/present/modules_user.png width=100%/>
  <br><br>
  <b>Fig 1.</b> Graphical interpretation of segments described in "basic specifications" section.
  <br><br>
</p>

## Features

<p align="center">
  <br>
  <img src=/gallery/present/modules_features.png width=100%/>
  <br><br>
  <b>Fig 1.</b> Graphical interpretation of segments described in "features" section.
  <br><br>
</p>
