# Open_NAS-Enclosures
Open Source NAS hardware

Specs and designs for a DIY, modular NAS enclosures.

## Goal 1
Create 3D printed enclosures to hold multiple HDDs 

## Goal 2
Incorporate existing backplanes into the 3d printed enclosures.
Backplanes like SuperMicro SATA743 or SATA823 or SATA836

## Goal 3
Create a DIY backplane for various drive configurations

The design requires on PCB onto which are 4 x SATA board connectors on one side of the PCB, and the other side of the PCB will have 1 x SFF-8087 connector and one Molex PATA 4 pin power connector.

The power connector should be a 90 deg connector and should be thru-hole mounted.

There should be 4 location on the PCB to mount the power connector depending on where the end user wants to mount it.

The 4 x SATA connetors should be directly (electrically) connected to the SFF-8087 connector. 

The "SATA BACKPLANE DESIGN" document specifies that all traces for one SATA connector should be the same length. What else should we know???
