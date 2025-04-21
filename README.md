# 🎛️ Filament Drying Box

A DIY project to build a cost-effective and efficient **3D printer filament drying box**. This setup helps maintain optimal filament quality by controlling temperature and humidity — perfect for makers and 3D printing enthusiasts.

---

## 📦 Features

- 💨 Active drying with controlled temperature
- 🌡️ Real-time temperature and humidity monitoring (DHT11/22 sensor)
- 🔥 Heating mechanism using a PTC heating element or similar
- 📟 LCD or OLED display for status updates
- ⚙️ Arduino/ESP-based microcontroller setup
- 🔋 Optional fan for air circulation
- ✅ Energy-efficient and modular design

---

## 🧰 Components Used

| Component              | Description                  |
|------------------------|------------------------------|
| Microcontroller        | Arduino UNO / ESP8266        |
| Temperature Sensor     | DHT11 / DHT22                |
| Display (Optional)     | LCD 16x2 / OLED I2C          |
| Heating Element        | PTC Heater / Ceramic Heater  |
| Fan (Optional)         | 5V/12V Cooling Fan           |
| Power Supply           | 12V DC Adapter               |
| Enclosure              | Plastic Box / Airtight Box   |

---

## 🔌 Circuit Diagram

📷 _[Insert circuit diagram or link here]_  
_You can upload an image or draw one using Fritzing._

---

## 🚀 How It Works

1. The sensor reads current temperature & humidity inside the box.
2. The microcontroller activates the heater if the humidity is high or temperature is below threshold.
3. The fan circulates air evenly (if present).
4. The display shows the real-time stats fetched from the sensor.
5. Filament stays dry and ready to print without moisture-related issues.

---

## 📁 Project Structure

