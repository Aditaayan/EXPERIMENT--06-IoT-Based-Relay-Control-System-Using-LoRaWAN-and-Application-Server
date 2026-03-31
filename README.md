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
<img width="1919" height="1198" alt="Untitled design (33)" src="https://github.com/user-attachments/assets/617c897c-e791-4b90-ad00-41facecd65a1" />

### 2. Network Server – Recent Events
![e34d43d7-f980-46ad-8a47-c89d4091dd2b](https://github.com/user-attachments/assets/b7fee9af-21dd-4fcf-97ba-2969e97509f7)
![ebc13ac5-121d-4bbb-a5dd-23c74c09e8cc](https://github.com/user-attachments/assets/23df7597-affd-4d92-85dc-664b1568c6e9)


### 3. Dashboard Command Sending
<img width="1919" height="1198" alt="Untitled design (28)" src="https://github.com/user-attachments/assets/5ccc1457-bcfb-424c-9e83-066ff9455fe9" />
<img width="1919" height="1198" alt="Untitled design (27)" src="https://github.com/user-attachments/assets/d57ac8bf-ad33-4a5b-936d-cf49b6a44c52" />
<img width="1919" height="1198" alt="Untitled design (26)" src="https://github.com/user-attachments/assets/0b9ee1ce-7138-4857-a56d-93e56169a141" />
<img width="1919" height="1198" alt="Untitled design (29)" src="https://github.com/user-attachments/assets/b735c9a5-6228-4147-acac-8628f082f719" />
<img width="1919" height="1198" alt="Untitled design (30)" src="https://github.com/user-attachments/assets/f0b15692-a209-48a5-8911-8f8d9ff49392" />
<img width="2612" height="1632" alt="omm" src="https://github.com/user-attachments/assets/855b60ba-9fcc-4aca-ab1b-bbc5822592cd" />
<img width="1919" height="1198" alt="Untitled design (31)" src="https://github.com/user-attachments/assets/7eb9c451-34da-4796-a4d2-b73b1187eff0" />
<img width="1919" height="1198" alt="Untitled design (32)" src="https://github.com/user-attachments/assets/49be1121-66c9-42bb-b13c-e3f05e6ed2f2" />



### 4. Relay Status Dashboard Output
### Bulb ON → Relay ON 
![70bd1fe6-aaae-4cc6-aaed-8dcb33865cb3](https://github.com/user-attachments/assets/8cc3e072-0331-4ce2-a0ad-f6afbeba63f0)
### Bulb OFF → Relay OFF
![6ac82a50-65d7-4f09-b41d-a12d0e8e2c32](https://github.com/user-attachments/assets/1eeb620b-14f1-4169-9449-5d0b65b4b34e)

## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
