# Android-nRF-UART

nRF UART app can be used to connect to Bluetooth® Smart devices running a custom Nordic Semiconductor UART service. When connected, the app can send and receive ASCII and UTF-8 text strings. 

This app works with the ble_app_uart project in the nRF51 SDK and the Bluetooth Smart SDK for Arduino. 

This app created as a demonstration for handling 128 bit proprietary UUID service and characteristics. 

The current version is x.x.x 

This source code can be compiled with Android Studio and Gradle. 

### Note
- Android 4.3 or later is required.
- Android Studio supported 

# New Features 20190807
- Retains address of last-connected Bluetooth device
- Will autoconnect to last-connect device address (if available) on startup
- Will automatically try to reconnect to last device if connection was disconnected for any reason other than user disconnect
- Any bytes received over Bluetooth will be appended to a log file in nRF-UART folder
