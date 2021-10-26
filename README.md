# BLE_web_tester
HTML file for quickly working with BLE notifications, animated plot for convenience.

Just customize the UUIds to access the service, writes, and notifications, and then the way the data is parsed into the plotY1 and plotY2 variables. 

You can add more plots if you need it's just plotly.

It's just set up to get one notification stream at a time, it also has some code for updating devices via BLE OTA that I borrowed from an ESP32 tutorial. 
