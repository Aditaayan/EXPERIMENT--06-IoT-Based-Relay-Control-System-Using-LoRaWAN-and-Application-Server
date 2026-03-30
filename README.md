# EXPERIMENT--06-IoT-Based-Relay-Control-System-Using-LoRaWAN-and-Application-Server
## Aim
To configure a LoRaWAN end device and monitor IR sensor data using a network server and dashboard visualization.

## Components Required
- LoRaWAN End Device-STM32
- LoRaWAN Gateway
- Application Server Dashboard
- Serial Port Utility
- Development Tools (STM32CubeIDE, STM32CubeProgrammer)

## Procedure
1. Open STM32CubeIDE and import the project from the realy-control project directory.
2. Select the LoRaWAN End Node project for the NUCLEO-WLE5JC board.
3. Clean all previous build files using the Clean Project option in the build configuration.
4. Build the project to generate the firmware files.
5. Flash the compiled firmware into the STM32 board using STM32CubeProgrammer with baud rate set to 9600.
6. Open the network server console and login using your registered email ID and password.
7. Register the device by selecting Device Types and adding the LoRaWAN device in the network server.
8. Open the Serial Port Utility  give the AT commands and verify device connection through the serial port utility
9. Create a dashboard on the application server by clicking the Add Dashboard option.
10. Add widgets and commands to visualize the relay status data.
11. Send control commands from the dashboard to control the relay.

## Output
### 1. Serial Port Utility – Network Server Connection
<img width="1919" height="1198" alt="Untitled design (18)" src="https://github.com/user-attachments/assets/2453b465-25ea-4a09-9085-4db60e03e773" />

### 2. Network Server – Recent Events
![e34d43d7-f980-46ad-8a47-c89d4091dd2b](https://github.com/user-attachments/assets/b7fee9af-21dd-4fcf-97ba-2969e97509f7)
![ebc13ac5-121d-4bbb-a5dd-23c74c09e8cc](https://github.com/user-attachments/assets/23df7597-affd-4d92-85dc-664b1568c6e9)


### 3. Dashboard Command Sending
<img width="1919" height="1198" alt="Untitled design (22)" src="https://github.com/user-attachments/assets/27467387-7ce6-4967-9169-8f2537419784" />
<img width="1919" height="1198" alt="Untitled design (21)" src="https://github.com/user-attachments/assets/0cb8054b-cb6f-47d4-a5ca-b0e665da114a" />
<img width="1919" height="1198" alt="Untitled design (15)" src="https://github.com/user-attachments/assets/9705bac2-079f-4acf-b817-87de9fa8d64b" />
<img width="1919" height="1198" alt="Untitled design (20)" src="https://github.com/user-attachments/assets/1e0a1330-0a0f-47f6-8fef-5b7fc9bf1fc7" />
<img width="1919" height="1198" alt="Untitled design (16)" src="https://github.com/user-attachments/assets/88dd88bc-b2b7-40d9-bcec-f3ac353d0c86" />
<img width="1919" height="1198" alt="Untitled design (12)" src="https://github.com/user-attachments/assets/a4d6b521-dab9-4f35-b038-c4af65b5ed2c" />
<img width="1919" height="1198" alt="Untitled design (19)" src="https://github.com/user-attachments/assets/d839b45f-5e78-4428-83ee-48a53cda5305" />
<img width="1919" height="1198" alt="Untitled design (14)" src="https://github.com/user-attachments/assets/fd3c15d7-7fcc-439e-87e9-d8d7a5a42e35" />
<img width="1919" height="1198" alt="Untitled design (17)" src="https://github.com/user-attachments/assets/b6f0b3b5-210b-4044-affb-f264c9036a44" />



### 4. Relay Status Dashboard Output
### Bulb ON → Relay ON 
![70bd1fe6-aaae-4cc6-aaed-8dcb33865cb3](https://github.com/user-attachments/assets/8cc3e072-0331-4ce2-a0ad-f6afbeba63f0)
### Bulb OFF → Relay OFF
![6ac82a50-65d7-4f09-b41d-a12d0e8e2c32](https://github.com/user-attachments/assets/1eeb620b-14f1-4169-9449-5d0b65b4b34e)

## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
