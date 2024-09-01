# **Covid Tackles with Smart Glass**

## **Introduction**
The **Covid Tackles with Smart Glass** is an innovative project aimed at keeping individuals safe from potential COVID-19 carriers. The smart glass is equipped with a temperature sensor that detects temperature within close proximity, and if it detects a temperature above 38.5°C, the glass triggers an alarm using a piezo buzzer and sends a notification to a mobile app. The app, connected to the glass via Bluetooth, displays the live temperature and provides access to important features such as nearby hospitals, doctors, pharmacies, vaccination centers, emergency contact numbers, and a pre-typed WhatsApp message for help.

![Project Image](https://github.com/user-attachments/assets/1e2d49ba-09c6-460e-a972-32d5d3aee887)


## **Working of the Project**
The smart glass utilizes the **DS18B20** temperature sensor, which detects the temperature of individuals within a 1-meter radius. When a temperature above 38°C is detected, the following actions occur:

1. The device activates a **piezo buzzer** to notify the user of a nearby individual with a potentially high fever.
2. Simultaneously, a notification is sent to the connected mobile app via Bluetooth.
3. The app displays the live temperature, and the status of any potential contact with a COVID-19 suspect is shown in real-time.
4. The app also allows users to access **information about nearby hospitals, doctors, pharmacies, and vaccination centers, along with options to call the COVID-19 helpline and send emergency messages via WhatsApp**.

<br>

![Covid App UI](https://github.com/user-attachments/assets/91a4c628-609f-46fc-8235-4c6530bcb628)

## **How the Project was Built**
This project was developed in two stages:

### **Stage 1: Initial Prototype**
In the first stage, the project was a simple circuit that used Bluetooth to send notifications to a mobile phone when the sensor detected a high temperature. The app displayed the notification, but the overall setup was fragile and lacked a robust user interface.

### **Stage 2: Final Version**
The final version of the project made significant improvements in both durability and functionality. In addition to Bluetooth notifications, a buzzer was integrated to immediately alert the user of potential COVID-19 exposure. The app interface was upgraded to include live temperature monitoring and status updates about nearby COVID-19 suspects. The app also became more interactive, featuring various essential functionalities such as hospital information, pharmacy details, and vaccination center locations. The final version is much more stable and user-friendly, providing a comprehensive solution for COVID-19 safety.

## **Components Used**
### **Hardware Components:**
1. **DS18B20 Temperature Sensor**: This sensor detects the highest temperature within a 1-meter range.
2. **Piezo Buzzer**: Emits an audible beep when a high temperature is detected.
3. **Arduino**: Acts as the central processing unit that controls the entire system.
4. **Smart Glass**: Integrated with the sensor and buzzer to detect temperature and alert the user.
5. **Bluetooth Module (HC-05/HC-06)**: Enables communication between the smart glass and the mobile app.
6. **Battery**: Powers the entire system.

### **Software Components:**
1. **Arduino IDE**: Used to program the Arduino microcontroller.
2. **Mobile App**: Developed for Android, the app connects via Bluetooth to the smart glass and displays live temperature data and other critical information.
3. **Google Maps API**: Integrated into the app to show nearby hospitals, doctors, pharmacies, and vaccination centers.
4. **WhatsApp API**: Allows the user to send a pre-typed emergency message directly from the app.

![Circuitry](https://github.com/user-attachments/assets/dbab546a-ab18-40f4-904c-46e5894c3e7c)

## **Methodology**
1. **Temperature Detection**: The DS18B20 sensor constantly monitors the temperature within a 1-meter range. When the temperature exceeds 38°C, the Arduino triggers a piezo buzzer and sends the data to the mobile app via the Bluetooth module.
   
2. **Mobile Notification**: The mobile app receives the temperature data and displays it in real-time. It also alerts the user with a notification indicating the detection of a potentially high temperature nearby.

3. **Additional Features**: The app contains integrated features for locating nearby hospitals, doctors, and pharmacies using Google Maps. The user can also access the nearest vaccination center or call the COVID-19 helpline directly from the app. Moreover, in an emergency, the user can send a pre-typed WhatsApp message for help.

## **User Interface**
The mobile app is designed to be intuitive and user-friendly. The home screen displays the current temperature detected by the smart glass, and additional screens provide easy access to other features such as hospital information, the COVID-19 helpline, and WhatsApp integration.

## **Conclusion**
The **Covid Tackles with Smart Glass** is a practical solution designed to help individuals stay safe in the midst of the COVID-19 pandemic. By detecting potentially dangerous temperatures and alerting the user immediately, this project offers an extra layer of protection in public settings such as schools and offices. With its integrated mobile app, users can stay informed about their health and have easy access to critical services during the pandemic.


## **License**
This project is licensed and copyright under Abhishek Gupta's. No commercial or domestic use of this idea or approach is permitted without the explicit permission of Abhishek Gupta.
