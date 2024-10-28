# Notes file for Helpers

This file is to hold notes about issues that you find learners have in the classroom, and how to help them quickly. If you find more than 2 or 3 people have similar issues,
please make a note in here so that future helpers can use your experience to help resolve issues quickly and get learners back on track.

## General

### Network connectivity, eduroam

#### At TU Delft

[Elviss] Connecting to TU Delft eduroam with a different institutional laptop (macOS) - issue due to certificate signing on macOS. This was the error message:

“The identity of the authentication server could not be established. Contact your network administrator to verify your configuration settings.”

The following steps helped:

1. From any Finder window, hit Command+Shift+G to bring up the “Go to the folder” window. Then enter the following: "/Library/Preferences/SystemConfiguration” and click Go.
2. Delete the “com.apple.network.eapolclient.configuration.plist” file which will prompt for administrator credentials. Enter your laptop password to give permission. Then, restart the laptop and connect to eduroam.
3. Connect to eduroam again with full institution details.


## Intro to R

### Installing RStudio

### Library issues

## Spreadsheets

## OpenRefine

## Visualisation

## Quarto
