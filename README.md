# 3D Printer Überguide
Welcome to the 3D Printer Überguide for the Cal Poly Humboldt Library Makerspace. 
This repository serves to document the norms of use and maintenance for our 3D printers, the Ender 3 S1 Pro and Ender 3 S1 Plus, for both students who wish to request a print as well as student assistants who need to clarify or troubleshoot a process with our printers. If there is anything you wish to add, please don't hesitate to open a pull request.

## Submission Norms
### Design Norms
Before you submit a file, either designed yourself or found online, please keep in mind that we use solely FDM (Fused Deposition Modeling) 3D printers. This means that designs made for SLA (resin) printers often will not come out right because of the detail required to print them. As a general rule of thumb, think to yourself, _can a moving part extruding a 0.4mm line of molten plastic print this?_ If you are unsure, don't hesitate to ask us first. Generally, objects with large unsupported overhangs, hanging parts, unsupported vertical parts, or very thin parts, as well as objects that are very complicated across multiple axes, may not print well. In the case that you are unsure of the printability of your design, please consult us and we can advise you on how you can possibly make your design more robust.
### Naming Conventions
Please make the submission file name descriptive and avoid special characters or spaces. Include your name in the submission file name.

## Print setup
### Filament change
Before starting a print, if the filament for the requested print is different than the one currently in place, heat the print head to the melting point of the current filament listed on the roll, typically 220C for PLA and 235C for PETG.
```
Ready >> Manual >> Nozzle temp.
```
Hold the filament gear release switch on top of the print head, remove the previous filament roll and adjust the temperature to the melting point of the new filament roll if it is higher than the previous filament. 
However, if the melting point of the new filament is lower (ie. going from PETG to PLA), leave the temperature at the melting point of the previous filament.
Hold the gear release switch, insert the filament and while still holding the gear release switch, push the filament in until filament starts coming out the nozzle. Then do the following:
```
Ready >> Manual >> In/Out >> 20mm
```
Repeat until the only filament/color coming out of the nozzle is the new one. Adjust the temperature to that of the current filament if you are immediately starting the print, or set it to zero if you are not immediately starting it.

### Leveling and Z-offset
