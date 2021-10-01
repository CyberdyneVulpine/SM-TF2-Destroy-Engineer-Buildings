# **[TF2] Smarter Doors**
#### Current Version: 1.0.0

## Description:
Allows admins to destroy or remove players' buildings.  
The 'clean remove' option removes the building without spawning metal.

## Commands:
-   **sm_destroy <target player> [target building] [clean removal 0/1]**
    - Target building can be  **sentry**,  **dispenser**, teleport  **entrance**, teleport  **exit**,  **tele**  (both entrance+exit), all (default).
    -   If using clean removal "1", buildings will just vanish, rather then blowing up and producing metal.  

## Cvars:
-   **sm_destroy_version** Plugin Version


## Install Instructions:
1.  Place  **DestroyBuildings.smx**  into your addons/sourcemod/plugins/ folder.


## ToDo:
-   Add support for "last" built target option
-   Menus
-   Logging

## Version History:
-   **v1.0.0**
    -   Initial Release
-   **V1.2.0**
    -   Support for targeting last-built building added.
    -   Fixes an issue with the if else stack
