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
<img width="1896" height="1105" alt="Screenshot 2026-03-19 112729" src="https://github.com/user-attachments/assets/6e4b88e9-c830-4c86-ab93-62ffa1bb265b" />


### 2. Network Server – Recent Events
<img width="1865" height="1081" alt="Screenshot 2026-03-19 112637" src="https://github.com/user-attachments/assets/dabdcd3a-8533-4eac-9cd0-a4c8aea573ca" />
<img width="1709" height="914" alt="Screenshot 2026-03-19 113235" src="https://github.com/user-attachments/assets/d3a831c0-c95f-473f-93bd-f8b6058116fd" />



### 3. Dashboard Command Sending
<img width="1916" height="1080" alt="Screenshot 2026-03-19 113130" src="https://github.com/user-attachments/assets/ce1ef27a-3c78-404c-a6ba-c5e709f5a9ec" />

### 4. Relay Status Dashboard Output



### DOOR ON → Relay ON 
<img width="1698" height="828" alt="Screenshot 2026-03-18 145927" src="https://github.com/user-attachments/assets/dda9e032-12a1-4ef0-9423-336a1bc46019" />

### DOOR OFF → Relay OFF
<img width="1669" height="883" alt="Screenshot 2026-03-18 150040" src="https://github.com/user-attachments/assets/fb45483b-c49f-4091-b055-c53eddd046fb" />

## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
