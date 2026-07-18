# IoT-Based-Women-Safety-Device-with-GPS-Health-Monitoring

<img width="1518" height="881" alt="image" src="https://github.com/user-attachments/assets/7f041614-8c09-42cf-99f7-c9bfde084adb" />

The system begins by initializing the hardware, including the ESP32 microcontroller and connected sensors such as GPS, SPO2, DHT11 (temperature and humidity), vibration sensor, and a panic button. Once initialized, the system continuously collects real-time data from these sensors. The collected data is then analyzed by the ESP32 to determine whether an emergency situation exists. This decision is based on predefined conditions or patterns, such as abnormal health readings, sudden movement, or manual activation through the panic button. 
If no emergency is detected, the system simply continues monitoring in a loop.

If an emergency is identified, the system triggers an alert process. It captures an image using the ESP32-CAM module and retrieves the current GPS location. This data is then transmitted wirelessly via Zigbee (transmitter) to a receiver module. The receiver passes the information back to the ESP32 for further processing.

<img width="919" height="486" alt="image" src="https://github.com/user-attachments/assets/98cb7e65-3bac-48b3-9b47-fed25c9c805a" />

After processing, the system displays an alert message on an LCD screen and activates a buzzer to provide an immediate local warning. Finally, it sends notifications to the user or relevant authorities, ensuring timely response. Once the alert is delivered, the process ends or resets for continuous monitoring.
# Energy Division

<img width="844" height="337" alt="image" src="https://github.com/user-attachments/assets/7f4e710d-adf3-47be-89c0-d065b50a4632" />
                                               
                                               Table:1 Transmitter circuit energy division
<img width="908" height="214" alt="image" src="https://github.com/user-attachments/assets/4b6d4285-bfcb-4850-8fab-dddf0f1dca5d" />
                                             
                                               Table:2 Receiver Circuit energy division
