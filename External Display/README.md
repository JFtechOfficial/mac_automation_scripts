## Display Utilities
### What does it do
When connecting to external display opens the following menubar apps:
* [Monitor Control](https://github.com/MonitorControl/MonitorControl) to control external monitor brightness and volume from MacOS with keys or TouchBar (in Extended Control Strip) 
* [Display Pilot](https://www.benq.com/en-us/monitor/software/display-pilot.html) to control external monitor sources, modes, etc. from MacOS (supported BenQ monitors only)
  1. Execute the app
  2. Close app window that annoyingly opens by default each time Display Pilot is executed
  
When disconnecting form external display quit the following menubar apps:
* [Monitor Control](https://github.com/MonitorControl/MonitorControl)
* [Display Pilot](https://www.benq.com/en-us/monitor/software/display-pilot.html)

### Requirements
* [Keyboard Maestro](https://www.keyboardmaestro.com/main/)
* [Monitor Control](https://github.com/MonitorControl/MonitorControl)
* [Display Pilot](https://www.benq.com/en-us/monitor/software/display-pilot.html)

### Installation
* Remove Monitor Control and Display Pilot from login items
* Import the `Display Utilities.kmmacros` file into Keyboard Maestro
* Edit the macro inserting [your mac user name](https://support.apple.com/guide/mac-help/if-you-forgot-your-user-or-account-name-mh35548/mac) in the field that requires it

---

## No Clamshell Mode
### What does it do
When the lid of your MacBook is closed, external monitor goes to sleep. To control this behaviour use the Clamshell Mode toggle in the status menu of Keyboard Maestro (menubar). Default Clamshell Mode: OFF. 

### Requirements
* [Keyboard Maestro](https://www.keyboardmaestro.com/main/)

### Installation
* Import the `No Clamshell Mode.kmmacros` and `Clamshell Mode: OFF.kmmacros` files into Keyboard Maestro

