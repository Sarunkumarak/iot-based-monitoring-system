# IoT-Based Flood Monitoring System

## Authors
- Arunkumar S  
- Bhabil Harithra A  
- Subbiah Arivalagan  

## Institution
- SRM Institute of Science and Technology, Chennai, Tamil Nadu  
- IBN SINA National College for Medical Studies, Jeddah, Saudi Arabia

## 📌 Abstract
This project presents an IoT-based flood monitoring system designed to collect real-time environmental data and issue instant alerts to prevent flood-related disasters. It integrates various sensors with an ESP8266 Node MCU for continuous monitoring of water levels, water flow, temperature, and humidity. The system transmits data wirelessly to a cloud platform, where it can be accessed and analyzed for early warning and disaster preparedness.

## 🔧 Components Used
- **ESP8266 Node MCU**: Wi-Fi enabled microcontroller
- **Ultrasonic Sensor (HC-SR04)**: Water level measurement
- **Water Flow Sensor**: Water flow speed detection
- **DHT11 Sensor**: Temperature and humidity monitoring
- **16x2 LCD with I2C**: Real-time data display
- **Power Supply Unit**: For continuous operation, can be solar-powered
- **Cloud Platform**: Firebase/Thingspeak for data logging and alerts

## 🧠 Features
- Real-time data collection and display
- Cloud-based data storage and remote monitoring
- Automatic alert system via mobile apps, SMS, or email
- Classification of water levels into Safe, Warning, and Danger zones
- Historical data logging for predictive analysis
- Proteus simulation for virtual testing

## 🛠️ Methodology
1. **Sensor Data Collection**: Gathers water level, flow, temperature, and humidity data.
2. **Data Transmission**: Sends sensor data via ESP8266 to the cloud.
3. **Notification System**: Issues warnings if thresholds are exceeded.
4. **Data Logging**: Stores historical sensor data for future analysis.

## 📱 Software
- **Arduino IDE**: Programming of ESP8266 using C/C++
- **Libraries Used**: `Wire.h`, `LiquidCrystal_I2C.h`, `DHT.h`
- **Communication Protocols**: MQTT or HTTP
- **Cloud Services**: Firebase, Thingspeak

## 📊 Results
- Effective real-time monitoring
- Reliable wireless communication and alert system
- Consistent and accurate sensor readings
- LCD and mobile UI provide instant feedback

## 🚀 Future Improvements
- AI/ML-based predictive flood modeling
- LoRa/GSM/Satellite-based communication integration
- Renewable energy sources (solar)
- Automatic flood barriers/valves
- Scalable for urban, rural, and coastal deployments

## 📚 References
1. Hadi et al., IOP Conf. Ser.: Earth Environ. Sci., 2020  
2. Siddique et al., EAI Trans. Internet of Things, 2023  
3. Rahman et al., J. Phys.: Conf. Ser., 2019  

## 📩 Contact
- 📧 bhabilharithra2@gmail.com  
- 📧 arunkumarak551100@gmail.com  
- 📧 arivu3@ibnsina.edu.sa

