# VisualStatusDisplay
![alt text](https://github.com/johnsonzhang434/VisualStatusDisplay/blob/master/Image.png)
# Requirements:
- Node.js

# How to start the application:
### Windows users:
1) Download the latest `visualstatusdisplay-win.exe` file under `Releases`
2) Double click the downloaded file
3) A security window should pop up asking if you want to run anyway
4) Click `more info` and `run anyway` or `allow`
5) The application should be running on localhost:1337 

### Mac users:
1) Download the latest `visualstatusdisplay-macos` file under `Releases`
2) Type the following command at the terminal command prompt to change directories to the location of the file you want to execute, relacing `/path/to/NameOfFile` with the full file location, called a path: 

`cd /path/to/NameOfFile`

3) Type the following command to set the file's executable bit using the chmod command, replacing `NameOfFile` with the name of the file you want to execute: 

`chmod +x ./NameOfFile`

4) Type the following to execute the file: 

`./NameOfFile`

If the file is not able to executed, try:
1) Go to your `System preferences`
2) Click on `Security and Privacy`
3) Under `General` at the bottom half of the display should have a prompt asking if you want to allow the app to run
4) Click `allow`
5) It should be running on localhost:1337 
### Linux users:
1) Download the latest `visualstatusdisplay-linux` file under `Releases`
2) Type the following command at the terminal command prompt to change directories to the location of the file you want to execute, relacing `/path/to/NameOfFile` with the full file location, called a path: 

`cd /path/to/NameOfFile`

3) Type the following command to set the file's executable bit using the chmod command, replacing `NameOfFile` with the name of the file you want to execute: 

`chmod +x ./NameOfFile`

4) Type the following to execute the file: 

`./NameOfFile`

If the file is not able to executed, try:
1) Go to your `System preferences`
2) Click on `Security and Privacy`
3) Under `General` at the bottom half of the display should have a prompt asking if you want to allow the app to run
4) Click `allow`
5) It should be running on localhost:1337 

### If you cloned this repository:
1) go to the directory of the application in your terminal
2) type `npm i` and hit `enter`
3) type `tsc` and hit `enter`
4) type `node dist/index.js` and hit `enter`
5) The application should be running on `localhost:1337` or on `your ipv4 address with port 1337`

## How to find your ipv4 address?
### Windows users:
1) On your computer search bar, search `cmd` and type `ipconfig` and hit `enter`
2) Your `ipv4 address` should be located under `Wireless Lan adapter Wi-Fi:`
3) It should be a number like: 192.168.0.XXX, and the XXX replaced with a 3 digit number

### Mac users:
1) Type the following command at the terminal command prompt: `ipconfig getifaddr en0` and hit `enter`
2) Your `ipv4 address` should be printed on the terminal
3) It should be a number like: 192.168.0.XXX, and the XXX replaced with a 3 digit number

## After starting the application: 
- the `display controller` should be hosted on your device on localhost:1337 and your device is the only one with access to the editor
- the display should be hosted on your ipv4 address `192.168.0.XXX:1337` and any device can view the display

# How to use the application:
- The user can edit the display by using the `display controller`
- The display is constantly checking to see if the user has updated their status
- If an update is detected, the display will be updated with the user's changes 

# Compiling to standalone
Install pkg
`npm i -g pkg`
Run pkg in the root folder:
`pkg .`
