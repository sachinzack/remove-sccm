# remove-sccm
Script to remove SCCM agent from PCs

This powershell script will remove the SCCM agent cleanly from any Windows device (tested on W7, W8, W10, W2012R2).
As part of this, it also resets the MDM authority. I've used this to prepare devices for "clean"/ standalone intune enrolment,
but the MDM authority reset should work with any other MDM agent.
