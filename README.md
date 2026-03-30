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
<img width="1919" height="1199" alt="564213149-3a5f7222-1a86-4773-aa01-0a32d5834270" src="https://github.com/user-attachments/assets/3dc5d4ef-773a-4790-842d-ab7ab35d243c" />

### 2. Network Server – Recent Events
![e34d43d7-f980-46ad-8a47-c89d4091dd2b](https://github.com/user-attachments/assets/b7fee9af-21dd-4fcf-97ba-2969e97509f7)
![ebc13ac5-121d-4bbb-a5dd-23c74c09e8cc](https://github.com/user-attachments/assets/23df7597-affd-4d92-85dc-664b1568c6e9)


### 3. Dashboard Command Sending
<img width="1919" height="1198" alt="Untitled design (15)" src="https://github.com/user-attachments/assets/9705bac2-079f-4acf-b817-87de9fa8d64b" />
<img width="1919" height="1198" alt="Untitled design (11)" src="https://github.com/user-attachments/assets/f091efee-6e95-4ac9-b25f-b5f7e3b16764" />
<img width="1919" height="1198" alt="Untitled design (12)" src="https://github.com/user-attachments/assets/a4d6b521-dab9-4f35-b038-c4af65b5ed2c" />
<img width="1919" height="1198" alt="Untitled design (13)" src="https://github.com/user-attachments/assets/f09f4c17-998b-4dd0-b09e-8ae4e76b7ca3" />
<img width="1919" height="1198" alt="Untitled design (14)" src="https://github.com/user-attachments/assets/fd3c15d7-7fcc-439e-87e9-d8d7a5a42e35" />
<img width="1919" height="1198" alt="Untitled design" src="https://github.com/user-attachments/assets/cb7e9a0b-0c82-4592-ae0a-c7a658594157" />



### 4. Relay Status Dashboard Output
### Bulb ON → Relay ON 
![70bd1fe6-aaae-4cc6-aaed-8dcb33865cb3](https://github.com/user-attachments/assets/8cc3e072-0331-4ce2-a0ad-f6afbeba63f0)
### Bulb OFF → Relay OFF
![6ac82a50-65d7-4f09-b41d-a12d0e8e2c32](https://github.com/user-attachments/assets/1eeb620b-14f1-4169-9449-5d0b65b4b34e)

## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
