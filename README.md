# TorontoFiles

This project is to keep the sector files all organized so we are working from the same version.

![new arrival box](https://github.com/user-attachments/assets/7e4a14d3-cb31-4e4d-8161-b3b4df4af530)

## Repack Information

This is a repack of [Toronto Files](https://github.com/TheT-Phil/TorontoFiles). The goal is to provide a ready-to-go package. 

### Profile
`CZYZ.prf` is the primary profile. It utilizes the realistic radar coverage and correlation mode. Ground tag outside of the radar coverage can not be correlated (squawk code in yellow even if they are on the correct code and mode C) and may have unreliable tag information when the mouse is not over the tag (for example, non-zero ground speed). 

`CZYZ-Easy.prf` uses Easy correlation mode and disregards the radar coverage. It is designed to be use on the minor tower positions and as the ground display. This profile shares most of the settings with the primary profile, except for the ones stored in `General settings.txt`. For example, the `Transparent TAG background` option in the symbology setting can be turned off in the Easy profile without affecting the primary profile.

### Plug-ins
Status Updater (`.updatetags`) and the latest nightly build of VATCANSitu plug-ins are included in the package.
