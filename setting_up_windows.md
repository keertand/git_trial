# Set up Windows

## Step 1: Change Gestures and Mouse sensitivity


## Step 2: Replace keys
  - Download Sharpkeys
  - Replace `rightclick` button to `CTRL`


## Step 3: Add Hot key shortcuts

Download AutoHotKeys software and install it:
`https://www.autohotkey.com/`

Use AutoHotKeys software
- go to desktop
- right click
- new
- Autohotkey script
- open the desktop folder, find the script file, and add these line
- Then, save it, double click to run the script and thats it, you are set.

```
!Left::Send {Home}
!Right::Send {End}
+!Left::Send {RShift down}{Home}{shift up}
+!Right::Send {RShift down}{End}{shift up}
```
