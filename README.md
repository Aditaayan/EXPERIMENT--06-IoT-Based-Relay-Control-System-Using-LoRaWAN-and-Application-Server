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


### 2. Network Server – Recent Events
![e34d43d7-f980-46ad-8a47-c89d4091dd2b](https://github.com/user-attachments/assets/b7fee9af-21dd-4fcf-97ba-2969e97509f7)
![ebc13ac5-121d-4bbb-a5dd-23c74c09e8cc](https://github.com/user-attachments/assets/23df7597-affd-4d92-85dc-664b1568c6e9)


### 3. Dashboard Command Sending
<img width="1919" height="1198" alt="Untitled design (16)" src="https://github.com/user-attachments/assets/3417efc9-ced1-433a-82ee-d89337c153dd" />
<img width="1919" height="1198" alt="Untitled design (17)" src="https://github.com/user-attachments/assets/5c2a4148-1f05-4d35-8800-07a41bf2ea10" />
<img width="1919" height="1198" alt="Untitled design (22)" src="https://github.com/user-attachments/assets/108e6a76-20a1-4b42-9089-66e1918df6cf" />
<img width="1919" height="1198" alt="Untitled design (12)" src="https://github.com/user-attachments/assets/1386c686-ccf5-47f7-b630-34419d99543e" />
<img width="1919" height="1198" alt="Untitled design (15)" src="https://github.com/user-attachments/assets/a9a9ce6b-e130-43dd-98f2-78818bef585c" />
<img width="1919" height="1198" alt="Untitled design (20)" src="https://github.com/user-attachments/assets/b21453bb-45fe-45cb-90a2-259be6f09397" />

<img width="1919" height="1198" alt="Untitled design (13)" src="https://github.com/user-attachments/assets/ec604b60-7a50-4287-9be8-c9cd82361438" />
<img width="1919" height="1198" alt="Untitled design (14)" src="https://github.com/user-attachments/assets/d686a7dd-e8c9-4a82-93a9-10dbb96c96df" />



### 4. Relay Status Dashboard Output
### Bulb ON → Relay ON 
![70bd1fe6-aaae-4cc6-aaed-8dcb33865cb3](https://github.com/user-attachments/assets/8cc3e072-0331-4ce2-a0ad-f6afbeba63f0)
### Bulb OFF → Relay OFF
![6ac82a50-65d7-4f09-b41d-a12d0e8e2c32](https://github.com/user-attachments/assets/1eeb620b-14f1-4169-9449-5d0b65b4b34e)

## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
