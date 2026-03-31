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
<img width="1919" height="1198" alt="Untitled design (34)" src="https://github.com/user-attachments/assets/ae30210f-1b9b-4ff2-b80a-99beda89d61c" />


### 2. Network Server – Recent Events
![e34d43d7-f980-46ad-8a47-c89d4091dd2b](https://github.com/user-attachments/assets/b7fee9af-21dd-4fcf-97ba-2969e97509f7)
![ebc13ac5-121d-4bbb-a5dd-23c74c09e8cc](https://github.com/user-attachments/assets/23df7597-affd-4d92-85dc-664b1568c6e9)


### 3. Dashboard Command Sending
<img width="1919" height="1198" alt="Untitled design (16)" src="https://github.com/user-attachments/assets/3417efc9-ced1-433a-82ee-d89337c153dd" />
<img width="1919" height="1198" alt="Untitled design (39)" src="https://github.com/user-attachments/assets/148e2f2e-7bc9-410b-bb37-3005c518f610" />

<img width="1919" height="1198" alt="Untitled design (38)" src="https://github.com/user-attachments/assets/60be8445-f362-41f2-bec3-f50ff1886d8e" />
<img width="1919" height="1198" alt="Untitled design (15)" src="https://github.com/user-attachments/assets/a9a9ce6b-e130-43dd-98f2-78818bef585c" />
<img width="1919" height="1198" alt="Untitled design (20)" src="https://github.com/user-attachments/assets/b21453bb-45fe-45cb-90a2-259be6f09397" />
<img width="1919" height="1198" alt="Untitled design (36)" src="https://github.com/user-attachments/assets/ac4ee54f-f5e6-4cbf-be42-64b3046540f4" />
<img width="1919" height="1198" alt="Untitled design (37)" src="https://github.com/user-attachments/assets/af6c4009-3bb1-4d36-a4bc-972e6e9fdd63" />

<img width="1919" height="1198" alt="Untitled design (35)" src="https://github.com/user-attachments/assets/cdebeed5-84f1-4e96-bcec-578b91e96644" />



### 4. Relay Status Dashboard Output
### Bulb ON → Relay ON 
![70bd1fe6-aaae-4cc6-aaed-8dcb33865cb3](https://github.com/user-attachments/assets/8cc3e072-0331-4ce2-a0ad-f6afbeba63f0)
### Bulb OFF → Relay OFF
![6ac82a50-65d7-4f09-b41d-a12d0e8e2c32](https://github.com/user-attachments/assets/1eeb620b-14f1-4169-9449-5d0b65b4b34e)

## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
