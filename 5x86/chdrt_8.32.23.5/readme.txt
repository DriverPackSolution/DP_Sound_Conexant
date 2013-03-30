Copyright 2012 Conexant Systems, Inc. All rights reserved.


This document is generic for Windows XP/2000/2003/Vista/Windows 7/Windows 8,
both 32bit and 64bit drivers.

Note 1: On Windows Vista and Windows 7/8 the Microsoft audio function driver
installs by default. Running the audio installation procedure below will
replace the Microsoft driver with the Conexant audio driver.

Note 2: On Windows XP and Windows 2000 (and early versions of 2003) you 
need to install a QFE to allow an HD Audio driver to install. This QFE is
made available by Microsoft, and it is required to update Operating System
components before installing the audio driver. The QFE contains the
required files and a readme which outlines installation procedure.
This QFE and these files are distributed by Microsoft only; please contact
them directly if you need to get them. The QFE's may be included in the
latest Service Packs for some Operating systems.


Note 3: Microsoft DirectX 9.0 or later is required

Note 4. On Windows XP/2000/2003 you need to install .NET 3.0 or later to allow
SmartAudio GUI application to install. Windows Vista, Windows 7 and later
include it natively.


INSTALLATION AND REMOVAL INSTRUCTIONS:


Installation or Update of Conexant audio Driver

Note 1: It is best to remove any previously installed audio driver from
the system before installing a new driver.

Note 2: On XP/2000/2003 if Windows detects the audiodevice hit Cancel 
then proceed to Step 1.


1.  Browse to the Conexant driver files location and double click setup.exe

2.  The Installation wizard will guide you through the installation.

3.  Restart the system when done.


Removal of the Conexant audio Driver

1.  Click on Start -> Settings -> Control Panel or
    click on Start -> Control Panel (depending on OS). 

2.  Double-click on the Add/Remove programs icon
    (called Programs And Features in Windows Vista and Windows 7/8).

3.  Click on Conexant driver item from the list and select "Remove" or
    "Uninstall"

4.  Restart the system when done.



Running an Unattended (Silent) Installation

1. From the task bar, click on Start -> Run

2. In the Run dialog box, type X:\path\setup -s
   (where X:\path is the path to the audio driver files)

3. Restart the system when done.


Running an Unattended (Silent) Uninstallation

1. From the task bar, click on Start -> Run

2. In the Run dialog box, type X:\path\setup -s -u -ichdrt.inf
   (where X:\path is the path to the audio driver files)

3.  Restart the system when done.


***********************************************************************
This driver is built for the Microsoft(R) Windows Operating Systems.

Copyright 2009-2012 Conexant Systems, Inc. All rights reserved.
***********************************************************************
8.2.0.0
