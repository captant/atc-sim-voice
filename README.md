# atc-sim-voice
Windows Speech Recognition Macros for [ATC-SIM.com](http://www.atc-sim.com/) command input.

Warning! This was originally developed for my own personal use. No guarantees that it will work on your machine. I am not a professional programmer and am not responsible if it breaks your computer.

## Installation
### Required Programs
1) Windows Speech Recognition. Usually, preinstalled. [Instructions](https://support.microsoft.com/en-us/help/4027176/windows-10-use-voice-recognition)
2) [Download Windows Speech Recognition Macros](https://www.microsoft.com/en-us/download/details.aspx?id=13045).
3) Windows Speech Recognition Macros (WSR Macros) creates a folder in Documents called Speech Macros. Copy atcsimvoice.WSRMac to this folder.

### Create Security Certificate for WSR Macros
WSR Macros allows control over core computer functionality (e.g., mouse clicks, keystrokes, opening/closing programs, etc.). Because of this, Windows wisely requires you to create a security certificate to allow macros to run.
1) Start Windows Speech Recognition Macros. This will automatically open Windows Speech Recognition if not already open. You will see its icon in your taskbar near the clock.
2) Right-click on the WSR Macros icon > Choose "Security..." > Click "Create Signing Certificate..." A window will open. Set security level to "Medium" if not already set. Then, click OK.

### Signing atcsimvoice.WSRMac
You must sign the specific macro you wish to run.
1) Right-click on the WSR Macros icon > Choose "Security..." > Click "Sign Speech Macros..." Explorer will open. Navigate to Documents/Speech Macros and choose the atcsimvoice.WSRMac file. Then, click Sign. You can now use the macro!

### Testing the Macro
atcsimvoice will only recognize voice commands when the [ATC-SIM website](http://www.atc-sim.com/) is open and in focus. This prevents it from activating when you don't want it to.
1) Ensure your microphone is on, Windows Speech Recognition is open, and Windows Speech Recognition Macros is open.
2) Ensure that the Windows Speech Recognition app is listening. (If it says "sleeping," it's not listening.)
3) With the [ATC-SIM website](http://www.atc-sim.com/) open and in focus, say "Radio check." If atcsimvoice is installed correctly, you should hear a computerized voice respond "Five by five." If you hear this, congrats! You've sucessfully installed atcsimvoice!

## Using Macro
atcsimvoice is a very simple macro. It can only input text into text boxes. To use:
1) Click into the atc-sim command box.
2) Say voice command. If recognized, text will be typed into the box automatically. If it is not recognized, WSR's default input box will appear. Say "Cancel," to get back to the atc-sim command box.
3) Pause between each command. The macro can only recognize one command at a time.
4) Once you have constructed your command, press enter on your keyboard to submit.
