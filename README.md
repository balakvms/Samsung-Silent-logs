# Samsung-Silent-logs

**Silent Log** Silent Logging is a built-in capability on Samsung device’s modem settings that silently backs up your Call and SMS logs from your phone with help of your device’s Kernel.
```
   Pre-requisite is that OTP will be needed from the Network Operatior/Device vendor
   Likely allowed in Test phones not for Commericial phones
```
## Step-by-step guide on how to set up Silent Log efficiently:

### Pre-Configuration

***Activate Flight Mode***
    
```
   a. Access your device's settings and enable Flight Mode.-
```

### Configuration
```
   a. Access the Dialer***
      Open the dialer app on your device.

   b. Enter Codes
      Dial *#9900# to access the configuration menu.

   c. Delete Old Dumps
      Select "Delete Dumpstate/Logcat."
      This action removes previous logs and dumps.
      It's advisable to delete the previous \log\ folder from the device's file explorer as well.

   d. Set Debug Level
      Choose "Debug Level" and set it to "MID."
      If the debug level is already set to "MID," proceed by rebooting the device.

   e. Turn On Silent Log
      After the device restarts, dial *#9900# again.
      Select the "Silent Log: OFF" button.
      Confirm your selection and choose "Default," then press "Ok."

   f. Disable Flight Mode
      Once configurations are set, turn off Flight Mode in the device settings.    Access the Dialer:
      Open the dialer app on your device.
```
### Testing Phase

***Start Testing***
```   
   a. Begin using the device as per your testing requirements.
```
***Post-Testing Configuration***
```
    a. Disable Silent Log:
        After completing the testing phase, access the dialer again with *#9900#.
        Select the "Silent Log: ON" button. This action will save CP silent logs.

    b. Run Dumpstate Logcat Modem Log:
        Dial *#9900# once more.
        Choose "Run Dumpstate Logcat Modem Log."
        Select "Copy to SD card."

    c. Access Logs:
        Navigate to Menu => Files Explorer => Device Storage => "Log" folder.
        Ensure that the folder contains ".qmdl" or ".qdss" files in the \log\cp\2020XXXXX\ directory.Testing Phase:
```

These steps will help you efficiently configure Silent Log on your device, enabling you to manage and retrieve logs effectively for diagnostic purposes.

