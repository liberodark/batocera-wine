## Wine package for BATOCERA
Is package for install wine on batocera v30 min.

## Creation of the package (Optional)
- Copy the entire batocera-wine directory to a directory of your choice on your BATOCERA system (eg: Packaging).
- Connect in SSH, then go to the Lutris or Proton folder.
- Run the command `batocera-makepkg`
- The package is generated in the upper directory (eg: Packaging).

## Installation
- Download the archive proton-5.13-3-x86_64.pkg.tar.xz to a directory of your choice on your BATOCERA system (ex: Packaging).
- Connect in SSH, then run the command `pacman -U proton-5.13-3-x86_64.pkg.tar.xz` in this folder.

## Remove the package
- Connect in SSH to your BATOCERA system
- Run the command `pacman -R proton`

## Links
BATOCERA -> https://batocera.org/

Wiki BATOCERA Pacman Manager -> https://wiki.batocera.org/pacman_package_manager

Exemple based on inrepublica work
