# google-it-support
This repository contains screenshots and notes from my first lab:  
installing, removing, and updating packages on Ubuntu.

## Screenshot 1 – Checking VLC & Updating System
This screenshot shows:
- Verifying whether the VLC Media Player package is available  
- Running a system update  
- Installing VLC Media Player
- https://github.com/ImanKasthuri/google-it-support/blob/af8fec5574904d74376f75c02946089a5ca30803/Screenshot1.png

## Screenshot 2 – Check & Install GIMP
This screenshot demonstrates:
- Checking if GIMP is available in the repositories 
- Installing GIMP on the system
- https://github.com/ImanKasthuri/google-it-support/blob/293c2acd107b3d7959f69387ac0db7c0e418acb4/Screenshot2.png

## Screenshot 3 – Remove/Uninstall GIMP
- This screenshot shows the process of uninstalling the GIMP application.
- https://github.com/ImanKasthuri/google-it-support/blob/293c2acd107b3d7959f69387ac0db7c0e418acb4/Screenshot3.png

## Screenshot 4 – Upgrade the System
- This screenshot shows upgrading all installed packages to their latest versions.
- https://github.com/ImanKasthuri/google-it-support/blob/293c2acd107b3d7959f69387ac0db7c0e418acb4/Screenshot4.png

## Commands Used
# Check whether VLC is available
dpkg -s vlc

# Update the system package lists
sudo apt-get update

# Install VLC Media Player
sudo apt-get install vlc

# Check whether GIMP is available
dpkg -s gimp

# Install GIMP
sudo apt-get install gimp

# Remove GIMP package
sudo apt-get remove gimp

# Upgrade all installed packages
sudo apt-get upgrade









