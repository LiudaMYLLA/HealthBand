# HealthBand

# Health Monitoring Bracelet for Elderly People

This project is a wearable health-monitoring bracelet designed for elderly individuals, especially in nursing homes or hospitals. It continuously monitors:
- Heart rate (BPM)
- Blood oxygen level (SpO₂)
- Fall detection

If connected to WiFi, it sends the collected data to a web server for real-time monitoring by caregivers or medical staff.

# Hardware Used

## Hardware Used

### Versions
| Stage        | Microcontroller |
|--------------|-----------------|
| Prototype    | ESP32           |
| Final Device | ESP32 Mini      |

### Components

| Component     | Purpose                                       |
|---------------|-----------------------------------------------|
| ESP32 / ESP32 Mini | Main MCU with WiFi capabilities           |
| **MAX30102**  | Pulse oximeter and heart rate monitor         |
| **GY-86**     | 10 DOF Sensor (MPU6050 + BMP180 + HMC5883L) for fall, pressure, compass |
| **TP4056**    | Lithium battery charging controller (with protection) |
| **Li-ion Battery** | Power supply                              |
| **Charging Block (5V)** | USB source to recharge the battery     |           
     

