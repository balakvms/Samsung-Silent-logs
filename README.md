# Samsung-Silent-logs

**Silent Log** Silent Logging is a built-in capability on Samsung device’s modem settings that silently backs up your Call and SMS logs from your phone with help of your device’s Kernel.
Pre-requisite is that OTP will be needed from the Network Operatior/Device vendor (Likely allowed in Test phones not for Commericial phones)

## Step-by-step guide on how to set up Silent Log efficiently:

### Pre-Configuration

    ***Activate Flight Mode***
    
    ```
    Access your device's settings and enable Flight Mode.-
    ```

### Configuration

***Access the Dialer***

```
Open the dialer app on your device.
```

***Enter Codes***
```
Dial *#9900# to access the configuration menu.
```

***Delete Old Dumps***
    ```
    Select "Delete Dumpstate/Logcat."
    This action removes previous logs and dumps. It's advisable to delete the previous \log\ folder from the device's file explorer as well.
    ```

    Set Debug Level:
        Choose "Debug Level" and set it to "MID."
        If the debug level is already set to "MID," proceed by rebooting the device.

    Turn Off Silent Log:
        After the device restarts, dial *#9900# again.
        Select the "Silent Log: OFF" button.
        Confirm your selection and choose "Default," then press "Ok."

    Disable Flight Mode:
        Once configurations are set, turn off Flight Mode in the device settings.    Access the Dialer:
        Open the dialer app on your device.

    Enter Codes:
        Dial *#9900# to access the configuration menu.

    Delete Old Dumps:
        Select "Delete Dumpstate/Logcat."
        This action removes previous logs and dumps. It's advisable to delete the previous \log\ folder from the device's file explorer as well.

    Set Debug Level:
        Choose "Debug Level" and set it to "MID."
        If the debug level is already set to "MID," proceed by rebooting the device.

    Turn Off Silent Log:
        After the device restarts, dial *#9900# again.
        Select the "Silent Log: OFF" button.
        Confirm your selection and choose "Default," then press "Ok."

    Disable Flight Mode:
        Once configurations are set, turn off Flight Mode in the device settings.

```
COMING SOON-
```
