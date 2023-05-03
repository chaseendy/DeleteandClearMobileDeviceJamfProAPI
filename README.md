# Delete_and_Clear_MD_JamfPro

This script will give users the ability to wipe and delete Mobile Devices on Jamf utilizing the Jamf API along with Token Bearer authentication. When run from Self Service, users will be presented with a box to input serial number. From there the user will see the devices' Jamf Pro information that have been recorded.

# USAGE:
    - Upload script to Jamf Pro and create a policy with this script as the payload. 
    - Make the Policy available in Self Service (For Technicians and Administrators)
    - Run the Policy, you'll be prompted to enter Device Serial Number 
      - From there the device will get the command to be wiped along with deleting the device record from Jamf while retaining the Prestage group.
